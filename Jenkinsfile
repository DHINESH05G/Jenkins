pipeline {
    agent any
     stage('clean the code ')
     {
        steps{bat 'mvn clean'}
     }
     stage('unit testing')
     {
        steps{ bat 'mvn test'}
     }
}
