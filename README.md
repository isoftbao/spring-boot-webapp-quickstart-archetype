Spring Boot Quickstart Maven Archetype
=========================================

[![Build Status](https://github.com/isoftbao/spring-boot-webapp-quickstart-archetype.svg?branch=master)](https://github.com/isoftbao/spring-boot-webapp-quickstart-archetype)
[![License Status](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/isoftbao/spring-boot-webapp-quickstart-archetype/master/LICENSE)

*Note : This repository is no longer maintained.*

Summary
-------
The project is a Maven archetype for Spring Boot web application.

Installation
------------

To install the archetype in your local repository execute following commands:

```sh
$ git clone https://github.com/isoftbao/spring-boot-webapp-quickstart-archetype.git
$ cd spring-boot-webapp-quickstart-archetype
$ mvn clean install
```

Create a project
----------------

```sh
$ mvn archetype:generate \
     -DarchetypeGroupId=com.isoftbao \
     -DarchetypeArtifactId=spring-boot-webapp-quickstart-archetype \
     -DarchetypeVersion=1.0.0 \
     -DgroupId=com.company \
     -DartifactId=webapp \
     -Dversion=1.0.0-SNAPSHOT \
     -DinteractiveMode=false
```

Run the project
----------------

```sh
$ mvn test spring-boot:run
```

Test on the browser
-------------------

```sh
http://localhost:8080/
```

Note: No additional services are required in order to start the application.
