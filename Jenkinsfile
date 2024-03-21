pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Bienvenu à Simplon'
                sh '''
                #!bin/bash
                ls -lrt
                '''
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
