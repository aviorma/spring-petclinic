# Project Title

Spring PetClinic Sample Application.

You should run build_petclinic_env.sh to set up the petclinic enviroment.

I uncommenct "spring.datasource.initialize=true" in the appliaction-mysql.properties file, which should
create PetClinic database and user by executing the "db/mysql/{schema,data}.sql" scripts


```
At the docker-compose.yml file you can see the port mapping that made according to my firewall at work.
please be aware of the nginx.conf file as well.
```

***
docker-compose version 1.19.0, build 9e633ef
docker-py version: 2.7.0
CPython version: 2.7.13
OpenSSL version: OpenSSL 1.0.1t  3 May 2016
OS: Ubuntu 14.04
***

## Getting Started

you should run build_petclinic_env.sh to set up the petclinic enviroment.

### Prerequisites

What things you need to install the software and how to install them

```
docker-compose version 1.19.0, build 9e633ef
docker-py version: 2.7.0
CPython version: 2.7.13
OpenSSL version: OpenSSL 1.0.1t  3 May 2016
OS: Ubuntu 14.04

```

### Installing

run build_petclinic_env.sh file.


### check the docker-compose env.

```
sudo docker-compose ps

```
## Deployment

clone the repository by:
```
git clone https://github.com/aviorma/spring-petclinic.git
cd spring-petclinic/trainologic_task/
./build_petclinic_env.sh

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## Authors

* **Avior Malkukian** - *Initial work* - [aviorma](https://github.com/aviorma)

