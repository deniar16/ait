# Simple Modular Project

    this project tested on shell script on windows environment using git bash


## How To Run

### 1. Gradle Wrapper
    you need gradle installed in your machine or build it from built in gradle that available in intellij
    - gradle wrapper

### 2. Build
    this process includes clean and build command

    you can build it based on it's module names
    - bin/build order inventory product
    - bin/build order inventory
    
    you can build all in one go 
    - bin/build

### 3. Deploy
    this process will deploy jar file inside build folder, make sure to build project first before run this command
    
    you can deploy it based on it's module names
    - bin/deploy order inventory product
    - bin/deploy order inventory
    
    you can deploy all in one go 
    - bin/deploy

### 4. Stop
    because deployment process uses background process, you need to manually kill it's port 

    run this command to kill all port used in this deployment
    - bin/stop

### 5. Open the service
    - Inventory
        - http://localhost:8081/
    - Order
        - http://localhost:8082/
    - Product
        - http://localhost:8083/

