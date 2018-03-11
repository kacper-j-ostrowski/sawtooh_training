# sawtooh_training
## Instalation
To build all application with docker-compose please run below command in terminal opened within directory contating sawtooh-default.yaml

docker-compose -f sawtooth-default.yaml up

After successful instalation of application it should be tested. In order to do so please run in second terminal window this command: 

docker exec -it sawtooth-client-default bash

Then execute this commmand: 

$ curl http://rest-api:8080/blocks

If it responded with JSON it means it works.
