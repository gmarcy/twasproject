WebSphere Traditional template repo for ODO devfile testing

The sample application contains a system microservice to retrieve the system properties and uses MicroProfile Config to simulate the status of the microservice, MicroProfile Health to determine the health of the microservice, and MicroProfile Metrics to provide metrics for the microservice.

## Run Sample application
    mvn clean package liberty:run-server

### Run Sample application with tests
    mvn clean install liberty:run-server

### Open url's in browser
    http://localhost:9080

