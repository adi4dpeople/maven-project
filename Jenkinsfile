pipeline {
    agent { dockerfile true }
    tools { 
        jdk 'java8'
        maven 'maven' 
    }
    stages {
        stage('Test') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}