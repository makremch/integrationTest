pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/makremch/integrationTest'
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
