pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build step'
                sleep 10
            }
        }
        stage('Test') {
            steps {
                echo 'Test step'
                sleep 11
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy step'
                sleep 10
            }
        }
        stage('Docker') {
            steps {
                echo 'Image step'
                sleep 10
            }
        }
    }
}