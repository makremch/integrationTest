pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/makremch/integrationTest'
            }
        }
        
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        
        
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
