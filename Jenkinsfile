pipeline {
    agent { dockerfile true 
    args '-v $HOME/.m2:/root/.m2' }
    tools { 
        maven 'maven' 
        jdk 'java8' 
    }
    stages {
        stage('Test') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}