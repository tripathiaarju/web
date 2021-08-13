pipeline {
    agent any
 
    stages {
        stage('Checking Version') {
            steps {
                sh 'mvn -version'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        
        stage('Deploying') {
            steps {
                echo 'Have to deploy'
            }
        }
    }
}
