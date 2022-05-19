# Java Basics


## Download / Clone this repository

- Download GIT if not installed already

  - For Windows Terminal/PowerShell

    - `winget install Git.Git`

  - For Linux Debian based OS

    - `sudo apt -y install git`

  - For Linux RHEL based OS

    - `sudo yum -y install git`

- Clone the repository

- `git clone https://github.com/kamal2k8s/java-demo.git` to clone the git repository.


## Installing Java JRE and JDK

- For Windows Terminal/PowerShell

  - `winget install Oracle.JavaRuntimeEnvironment` can be used to install JRE.

  - `winget install AdoptOpenJDK.OpenJDK.16` cane be used to install JDK 16.


## Creating a Java Project

1. Install Java extensions in VS Code and press `Ctrl+Shift+P` and search for create project.

2. Give information about the project and create one.


## Create Java Class file from .Java File

- Just use command `javac -d ./bin/ ./src/*.java`

    - Here `-d` is for specifying the directory.

    - `*` is for specifying the all java files in a folder.


## Create Java Jar file from .Class or .Java File

- `jar.exe cf .\build\app.jar .\bin\App.class` used to create the jar file from class or java file.