# Spring PetClinic Sample Application.

You should run build_petclinic_env.sh to set up the petclinic enviroment.

** I uncommenct "spring.datasource.initialize=true" in the appliaction-mysql.properties file, which should 
create PetClinic database and user by executing the "db/mysql/{schema,data}.sql" scripts
** 

```
At the docker-compose.yml file you can see the port mapping that made according to my firewall at work.
please be aware of the nginx.conf file as well.

```
Docker version 1.13.1, build 092cba3
OS: Ubuntu 14.04
```
