# Spring PetClinic Sample Application.

## Getting Started

At the docker-compose.yml file you can see the port mapping that made according to my firewall at work.
please be aware of the nginx.conf file as well.

I uncommenct "spring.datasource.initialize=true" in the appliaction-mysql.properties file, which should
create PetClinic database and user by executing the "db/mysql/{schema,data}.sql" scripts


### Prerequisites

tools i worked with:

```
docker-compose version 1.19.0, build 9e633ef
docker-py version: 2.7.0
CPython version: 2.7.13
OpenSSL version: OpenSSL 1.0.1t  3 May 2016
OS: Ubuntu 14.04

```

### Installing

run build_petclinic_env.sh file.


## check the docker-compose env.

```
sudo docker-compose ps
```

## Deployment

clone the repository:
```
git clone https://github.com/aviorma/spring-petclinic.git
cd spring-petclinic/trainologic_task/
./build_petclinic_env.sh
```

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## Authors

* **Avior Malkukian** - *Initial work* - [aviorma](https://github.com/aviorma)

