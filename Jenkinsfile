pipeline {
    agent any
 
    stages {
        stage('Checking Version') {
            steps {
                sh 'mvn -version'
            }
        }
        stage('Compiling') {
            steps {
                sh 'mvn clean build'
            }
        }
    }
}
