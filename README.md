##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t agunuworld/java-app:java-1.0 .
    
##### push image to repo

    docker tag java-app demo-app:java-1.0
