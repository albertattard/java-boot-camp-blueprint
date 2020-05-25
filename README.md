# Java Boot Camp Starter Project

This repository acts as a starting point for the [Java boot camp](https://github.com/albertattard/java-boot-camp).  Instead of creating a project from scratch using [`gradle init`](https://github.com/albertattard/java-boot-camp/blob/master/01%20-%20Primer.md#create-a-project-using-gradle), for example, you can clone this repository.

This project [requires Java 14](https://github.com/albertattard/java-boot-camp/blob/master/01%20-%20Primer.md#setup-environment-sdkman).

Following are some useful commands.  All commands are expected to be executed form within the project's directory.

1. Build project using Gradle

    ```bash
    $ ./gradlew clean build
    ```

1. Run project using Gradle

    ```bash
    $ ./gradlew clean run
    ```

    Using the class specified by the `mainClassName` definition as the project's entry point.

    ```groovy
    application {
      mainClassName = 'demo.App'
    }
    ```

1. Run application

    ```bash
    $ java -jar build/libs/demo.jar
    ```

1. Create Docker Image

    ```bash
    $ docker build . -t demo:local
    ```

1. Run Docker Image

    ```bash
    $ docker run -it demo:local
    ```
