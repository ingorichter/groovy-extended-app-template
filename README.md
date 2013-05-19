Groovy Extendend Application project template
---------------------------------------------

You have just created an extended Groovy application with gradle wrapper support. You will have support for Cobertura and Codenarc right from the start. There is a standard project structure for source code and tests.

In this project you get:

* A Gradle build file with pre-built Gradle wrapper
* A Cobertura setup
* A basic Codenarc configuration (config/codenarc/codenarc.xml)
* Using the eclipse and idea plugin to generate project files to use with these IDE's
* A standard project structure:

    <proj>
    |
    +- README.md
    +- VERSION
    +- build.gradle
    +- config
         |
         +- codenarc
                |
                +-codenarc.xml 
    +- gradle
         |
         +- wrapper
               |
               +- gradle-wrapper.jar
               +- gradle-wrapper.properties
    +- gradle.properties
    +- gradlew
    +- gradlew.bat
    +- src
        |
        +- main
             |
             +- groovy
        +- test
             |
             +- groovy
