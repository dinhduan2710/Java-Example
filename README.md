# Java-Example

**Link: https://linuxiac.com/how-to-install-java-on-ubuntu-24-04-lts/**

## Install Java in Ubuntu

1. Update the package
    - sudo apt update

2. Install OpenJDK
    - sudo apt install openjdk-17-jdk

    ### Install OpenJDK 17:
        - sudo apt install openjdk-17-jdk
    
    ### Install the latest OpenJDK version available
        - sudo apt install default-jdk

3. Check Install
    - java --version

4. Set Default Java Version
    - sudo update-alternatives --config java

5. Setting JAVA_HOME
    #### Open the environment variables
        - sudo nano /etc/environment
    #### Add the following line at the end of the file
        - JAVA_HOME="/usr/lib/jvm/java-17-openjdk-amd64"
    #### Apply the changes
        - source /etc/environment
    #### check
        - echo $JAVA_HOME

