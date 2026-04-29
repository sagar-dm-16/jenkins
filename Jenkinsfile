// Jenkinsfile
pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning happens automatically'
            }
        }

        stage('Build') {
            steps {
                bat 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Hello'
            }
        }
    }
}
