pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Compile the Java project
                bat 'hello-world' // List files to verify the path
                bat 'javac -d target src\\main\\java\\com\\example\\App.java'
            }
        }
        stage('Test') {
            steps {
                // Run unit tests (if any)
                echo 'No tests to run.'
            }
        }
        stage('Deploy') {
            steps {
                // Deploy the application (this is just a placeholder)
                echo 'Deploying the application...'
            }
        }
    }
}