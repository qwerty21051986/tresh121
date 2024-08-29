# Project Maven

## How to use for Maven

+ Navigate to the project directory

+ Build the project

    + run `mvn validate` to execute the validation phase explicitly

    + run `mvn clean install` to install the artifact to a local repository

+ Run the game:

    + run `mvn javafx:run` or `java -jar ".\target\project-maven-1.0.jar"`

## How to use for Gradle

+ Navigate to the project directory

+ Build the project

    +
    run `mvn install:install-file -Dfile=".\project-maven\lib\desktop-game-engine.jar" -DgroupId="com.javarush" -DartifactId="desktop-game-engine" -Dversion="1.0" -Dpackaging=jar`
    to add the local artifact to a local repository

    + run `gradle clean build` to create the artifact

+ Run the game:

    + run `java -jar ".\build\libs\project-maven-1.0.jar"`