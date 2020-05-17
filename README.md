# Java Boot Camp Starter Project

Useful commands

1. Build project using Gradle

    ```bash
    $ ./gradlew clean build
    ```

1. Run project using Gradle

    ```bash
    $ ./gradlew clean run
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
