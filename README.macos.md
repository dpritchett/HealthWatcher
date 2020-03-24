# Getting started on MacOS

## Setup
- Download Intellij IDEA CE: https://www.jetbrains.com/idea/download/
- Install oracle JDK 8: https://www.oracle.com/java/technologies/javase-jdk8-downloads.html
- Install the android SDK via homebrew: https://formulae.brew.sh/cask/android-sdk

## Repo clone and setup
- Clone the git repo
- Export `JAVA_HOME` and `ANDROID_HOME` variables similar to these:
    ```sh
    ANDROID_HOME=/usr/local/share/android-sdk
    JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_241.jdk/Contents/Home
    ```

- Open the project in IntelliJ
- Follow Intellij's prompts to point it to your preinstalled JDK8 and Android SDK using the same paths as your earlier environment variables.
- Click Build -> Build Project.
