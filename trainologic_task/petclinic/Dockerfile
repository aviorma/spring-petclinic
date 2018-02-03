FROM java:openjdk-8-jdk
MAINTAINER AVIOR MALKUKIAN


ENV MAVEN_VERSION 3.3.9
RUN curl -fsSL https://archive.apache.org/dist/maven/maven-3/$MAVEN_VERSION/binaries/apache-maven-$MAVEN_VERSION-bin.tar.gz | tar xzf - -C /usr/share \
  && mv /usr/share/apache-maven-$MAVEN_VERSION /usr/share/maven \
  && ln -s /usr/share/maven/bin/mvn /usr/bin/mvn

ENV MAVEN_HOME /usr/share/maven

# Cloning my forked repository.
RUN git clone https://github.com/aviorma/spring-petclinic.git /usr/src/app/
WORKDIR /usr/src/app/

RUN mvn package -DskipTests

# expose the web app port.
EXPOSE 9966

ENTRYPOINT ["mvn", "spring-boot:run"]
