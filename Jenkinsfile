pipeline {

    agent any

    stages {
        stage('Git Checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/upa-io/microservice-poc.git'
            }
        }
        stage('Unit Testing'){
            steps{
                sh 'mvn test'
            }
        }
    }
}