pipeline {
    agent any

    environment {
        DOCKER_CREDENTIAL = "docker"
        IMAGE_NAME = ""
    }

    stages {
        stage('Build Java Application') {
            steps {
                bat "javac Hello.java"
            }
        }

        stage('Run Java Program') {
            steps {
                bat "java Hello"
            }
        }
    }
}
