## spring-boot-intro

### What is Spring Boot?

- Spring Boot provides a good platform for Java developers to develop a stand-alone and production-grade spring application that you can just run.

### Project Structure

alfa-tr/\
├── backend/ # Spring Boot API\
│ ├── src/\
│ │ └── main/\
│ │ ├── java/com/alfa/api/\
│ │ │ ├── controller/\
│ │ │ │ └── ShipController.java\
│ │ │ ├── model/\
│ │ │ │ └── ShipInfo.java\
│ │ │ └── AlfaTrApplication.java\
│ │ └── resources/\
│ │ └── application.properties\
│ └── pom.xml\
|\
├── frontend/ # React UI\
│ ├── public/\
│ ├── src/\
│ │ ├── components/\
│ │ │ └── ShipInfoCard.jsx\
│ │ ├── services/\
│ │ │ └── api.js\
│ │ └── App.jsx\
│ └── package.json\

### Installation

#### Start Maven Project

$ mvn archetype:generate -DgroupId=com.alfa -DartifactId=alfatr-api -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
$ cd alfatr-api
