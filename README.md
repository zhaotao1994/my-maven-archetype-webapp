## Maven Webapp Archetype
`maven-archetype-webapp` is an archetype which generates a sample Maven webapp project:

    project
    |-- pom.xml
    |-- src
        |-- main
            |-- java
                |-- $package
            |-- resources
            |-- webapp
                |-- WEB-INF
                    |-- web.xml
                |-- index.html
        |-- test
            |-- java
### Usage
To generate a new project from this archetype, type:

    mvn archetype:generate -DarchetypeGroupId=vip.zhaotao -DarchetypeArtifactId=my-maven-archetype-webapp -DarchetypeVersion=1.0