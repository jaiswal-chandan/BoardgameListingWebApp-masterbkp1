pipeline {
    agent any
    
    tools { 
        jdk 'jdk17'
        maven 'maven'
    }

    stages {
        
        stage('Compile') {
            steps {
               sh "mvn compile"
            }
        }
        
        stage('Test') {
            steps {
                sh "mvn test"
            }
        }
        
        stage('Package') {
            steps {
                sh "mvn package"
            }
        }
        
    
    }
}
