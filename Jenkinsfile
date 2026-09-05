pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Java application'
                bat 'javac Hello.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Java application'
                bat 'java Hello'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}