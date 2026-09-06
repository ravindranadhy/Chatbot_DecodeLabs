# Chatbot DecodeLabs

## Overview
Chatbot DecodeLabs is a simple Python-based chatbot project developed as part of the Decode Labs assignment. The project demonstrates basic chatbot functionality using Python.

## Features
- Interactive chatbot
- User-friendly command-line interface
- Simple question and response system
- Easy to understand and modify

## Technologies Used
- Python 3
- Visual Studio Code

## Project Files

- chatbot.py
  - Basic chatbot implementation.

- chatbot_Dictionary.py
  - Dictionary-based chatbot implementation.

## How to Run

1. Install Python 3.
2. Open the project folder.
3. Run one of the following commands:

```bash
python chatbot.py
```

or

```bash
python chatbot_Dictionary.py
```

## Author

**Ravindranadhy**

## Repository

This project was created for the Decode Labs assignment.


# Chatbot DecodeLabs

## Overview
Chatbot DecodeLabs is a simple Python-based chatbot project developed as part of the Decode Labs assignment. The project demonstrates basic chatbot functionality using Python.

## Features
- Interactive chatbot
- User-friendly command-line interface
- Simple question and response system
- Easy to understand and modify

## Technologies Used
- Python 3
- Visual Studio Code

## Project Files

- chatbot.py
  - Basic chatbot implementation.

- chatbot_Dictionary.py
  - Dictionary-based chatbot implementation.

## How to Run

1. Install Python 3.
2. Open the project folder.
3. Run one of the following commands:

```bash
python chatbot.py
```

or

```bash
python chatbot_Dictionary.py
```

## Author

**Ravindranadhy**

## Repository

This project was created for the Decode Labs assignment.




maven java project
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0
         http://maven.apache.org/xsd/maven-4.0.0.xsd">

    <modelVersion>4.0.0</modelVersion>

    <groupId>com.example</groupId>
    <artifactId>maven-java-project</artifactId>
    <version>0.0.1-SNAPSHOT</version>
    <packaging>jar</packaging>

    <name>maven-java-project</name>
    <url>http://maven.apache.org</url>

    <properties>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
        <maven.compiler.source>21</maven.compiler.source>
        <maven.compiler.target>21</maven.compiler.target>
    </properties>

    <dependencies>

        <!-- JUnit for testing -->
        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>3.8.1</version>
            <scope>test</scope>
        </dependency>

        <!-- Gson -->
        <dependency>
            <groupId>com.google.code.gson</groupId>
            <artifactId>gson</artifactId>
            <version>2.10</version>
        </dependency>

    </dependencies>

    <build>
        <plugins>

            <!-- Configure Java compiler -->
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-compiler-plugin</artifactId>
                <version>3.13.0</version>
                <configuration>
                    <source>21</source>
                    <target>21</target>
                </configuration>
            </plugin>

            <!-- Create executable JAR -->
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-jar-plugin</artifactId>
                <version>3.4.2</version>
                <configuration>
                    <archive>
                        <manifest>
                            <mainClass>
                                com.example.maven_java_project.App
                            </mainClass>
                        </manifest>
                    </archive>
                </configuration>
            </plugin>

        </plugins>
    </build>

</project>

Cm
<?xml version="1.0" encoding="UTF-8"?>

<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0
         http://maven.apache.org/xsd/maven-4.0.0.xsd">

    <modelVersion>4.0.0</modelVersion>

    <!-- Project Information -->
    <groupId>CSMB</groupId>
    <artifactId>CEMS</artifactId>
    <packaging>war</packaging>
    <version>0.0.1-SNAPSHOT</version>
    <name>CEMS</name>

    <!-- Java Configuration -->
    <properties>
        <maven.compiler.source>8</maven.compiler.source>
        <maven.compiler.target>8</maven.compiler.target>
    </properties>

    <!-- Dependencies -->
    <dependencies>

        <!-- JUnit -->
        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>4.13.2</version>
            <scope>test</scope>
        </dependency>

        <!-- Database Library -->
        <dependency>
            <groupId>com.mysql</groupId>
            <artifactId>mysql-connector-j</artifactId>
            <version>8.0.33</version>
        </dependency>

        <!-- Another Dependency -->
        <dependency>
            <groupId>org.example</groupId>
            <artifactId>cems-utils</artifactId>
            <version>1.0</version>
        </dependency>

    </dependencies>

    <!-- Build Configuration -->
    <build>

        <plugins>

            <!-- Maven Compiler Plugin -->
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-compiler-plugin</artifactId>
                <version>3.8.1</version>

                <configuration>
                    <source>8</source>
                    <target>8</target>
                </configuration>

            </plugin>

        </plugins>

    </build>

</project>

Food system

<?xml version="1.0" encoding="UTF-8"?>

<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0
         http://maven.apache.org/xsd/maven-4.0.0.xsd">

    <modelVersion>4.0.0</modelVersion>

    <!-- Project Information -->
    <groupId>FoodApp</groupId>
    <artifactId>FoodOrderingSystem</artifactId>
    <packaging>war</packaging>
    <version>0.0.1-SNAPSHOT</version>
    <name>Food Ordering System</name>

    <!-- Project URL -->
    <url>localhost:8080/FoodSystem</url>

    <dependencies>

        <!-- Java Servlet API -->
        <dependency>
            <groupId>javax.servlet</groupId>
            <artifactId>servlet-api</artifactId>
            <version>3.1-b05</version>
        </dependency>

        <!-- MySQL Connector -->
        <dependency>
            <groupId>com.mysql</groupId>
            <artifactId>mysql-connector-j</artifactId>
            <version>8.0.33</version>
        </dependency>

        <!-- JUnit -->
        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>4.13.2</version>
            <scope>test</scope>
        </dependency>

    </dependencies>

    <build>

        <finalName>Food-System</finalName>

        <plugins>

            <!-- Tomcat Maven Plugin -->
            <plugin>
                <groupId>org.apache.tomcat.maven</groupId>
                <artifactId>tomcat7-maven-plugin</artifactId>
                <version>2.2</version>
            </plugin>

        </plugins>

    </build>

</project>

Hospital System

<?xml version="1.0" encoding="UTF-8"?>

<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0
         https://maven.apache.org/xsd/maven-4.0.0.xsd">

    <modelVersion>4.0.0</modelVersion>

    <!-- Project group -->
    <groupId>SE.HospitalMgmtSystem</groupId>

    <!-- Project name -->
    <artifactId>HospitalMgmtSystem</artifactId>

    <!-- Project version -->
    <version>1.0-SNAPSHOT</version>

    <!-- Default packaging is jar -->
    <packaging>jar</packaging>

    <properties>
        <!-- Java version -->
        <maven.compiler.source>21</maven.compiler.source>
        <maven.compiler.target>21</maven.compiler.target>
    </properties>

    <dependencies>

        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>4.13.2</version>
            <scope>test</scope>
        </dependency>

    </dependencies>

    <build>

        <plugins>

            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-compiler-plugin</artifactId>
                <version>3.13.0</version>

                <configuration>
                    <release>21</release>
                </configuration>

            </plugin>

        </plugins>

    </build>

</project>
