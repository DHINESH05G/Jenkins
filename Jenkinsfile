pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                checkout scm
                sh 'make build' // Replace with your build command
            }
        }
        stage('Test') {
            steps {
                bat 'make test' // Replace with your test command
                junit '**/target/test-*.xml' // Adjust the path to your test results
            }
        }
        stage('Deploy') {
            steps {
                bat 'make deploy' // Replace with your deploy command
            }
        }
    }
}
