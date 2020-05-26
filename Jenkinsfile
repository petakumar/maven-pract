pipeline {
    agent any 
    stages {
        stage('Clean') { 
            steps {
                
                sh label: '', script: '''mvn clean'''

            }
        }
        stage('Test') { 
            steps {
            sh label: '', script: '''mvn test'''
 
            }
        }
        stage('Deploy') { 
            steps {
                sh label: '', script: '''mvn package'''

            }
        }
    }
}
