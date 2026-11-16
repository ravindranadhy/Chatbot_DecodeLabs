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






Sample Script

pipeline {
    agent any

    stages {
        stage('Hello 1') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Hello3') {
            steps {
                echo 'Hello 3'
            }
        }
    }
}



Java Script

pipeline {
    agent any

    tools {
        maven 'MAVEN_HOME'
    }

    stages {

        stage('Git Clone & Clean') {
            steps {
                bat "if exist maven-java-project rmdir /s /q maven-java-project"
                bat "git clone https://github.com/ravindranadh022/maven-java-project.git"
                bat "mvn clean -f maven-java-project/pom.xml"
            }
        }

        stage('Install') {
            steps {
                bat "mvn install -f maven-java-project/pom.xml"
            }
        }

        stage('Test') {
            steps {
                bat "mvn test -f maven-java-project/pom.xml"
            }
        }

        stage('Package') {
            steps {
                bat "mvn package -f maven-java-project/pom.xml"
            }
        }
    }
}


Web Script

pipeline {
    agent any

    tools {
        maven 'MAVEN_HOME'
    }

    stages {

        stage('Git Clone & Clean') {
            steps {
                bat "if exist mw rmdir /s /q mw"
                bat "git clone https://github.com/ravindranadh022/mw.git"
                bat "mvn clean -f mw/pom.xml"
            }
        }

        stage('Install') {
            steps {
                bat "mvn install -f mw/pom.xml"
            }
        }

        stage('Test') {
            steps {
                bat "mvn test -f mw/pom.xml"
            }
        }

        stage('Package') {
            steps {
                bat "mvn package -f mw/pom.xml"
            }
        }
}







Credentials
        pipeline {
    agent any

    tools {
        maven 'MAVEN_HOME'
    }

    stages {

        stage('Git Clone & Clean') {
            steps {
                bat "if exist mw rmdir /s /q mw"
                bat "git clone https://github.com/ravindranadh022/mw.git"
                bat "mvn clean -f mw/pom.xml"
            }
        }

        stage('Install') {
            steps {
                bat "mvn install -f mw/pom.xml"
            }
        }

        stage('Test') {
            steps {
                bat "mvn test -f mw/pom.xml"
            }
        }

        stage('Package') {
            steps {
                bat "mvn package -f mw/pom.xml"
            }
        }

        stage('Deploy to Tomcat') {
            steps {
                deploy adapters: [
                    tomcat9(
                        credentialsId: '19123888-cd0f-4f03-90da-78951963782f',
                        url: 'http://localhost:8083'
                    )
                ],
                contextPath: 'mw',
                war: 'mw/target/*.war'
            }
        }
    }
}
    }



















minikube start --driver=docker
minikube status
kubectl get pods
kubectl get deployments
kubectl get services
kubectl get replicasets
kubectl get nodes
kubectl get all
kubectl create deployment mynginx --image=nginx
kubectl get pods
kubectl get deployments
kubectl get services
kubectl describe pods
kubectl expose deployment mynginx --type=NodePort --port=80 --target-port=80
kubectl scale deployment mynginx --replicas=4
kubectl get pods
kubectl port-forward svc/mynginx 8084:80


Nagios
docker pull jasonrivers/nagios:latest

docker run --name nagiosdemo -p 8888:80 jasonrivers/nagios:latest

docker stop nagiosdemo

docker rm nagiosdemo

docker images

docker rmi jasonrivers/nagios:latest
