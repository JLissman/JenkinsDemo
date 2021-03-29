pipeline{
    agent any
    tools{
        maven 'maven'
    }

    stages{
        stage('Build'){
            steps{
                echo 'Hello world'
                sh 'java --version'
                sh 'mvn --version'
                sh 'mvn clean compile'
            }
        }
    }
}