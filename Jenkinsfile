pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '411b1e20-f1d7-420b-88be-aabee3e9f2d0', url: 'https://github.com/makremch/integrationTest']]])
            }
        }}
        
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
