# Automatic Irrigation System App:

## Technology Used: 
* spring boot
* Java 11 
* MysqlDatabase (docker-compose)
* libs: FeignClient(client calling), Resilience4j retry

## Steps To Run The App:
1. run the docker-compose file under the resources folder in the project. 
2. using this command: docker-compose -f docker-compose.yml up .
3. when the application starts it will automatically generates the ddl and create tables for you.

## Sample:
* attached sample request file that can be imported in postman as a collection: in the resource folder for the below endpoints plotofland,irrigationslot,sensorDevice.
