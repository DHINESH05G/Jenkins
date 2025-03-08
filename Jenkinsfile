pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                checkout scm
                bat 'mvn clean' // Replace with your build command
            }
        }
    }
}
