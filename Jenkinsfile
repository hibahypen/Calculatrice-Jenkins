pipeline {
    agent any

    stages {
        stage('Installation') {
            steps {
                bat 'npm install'
            }
        }
        stage('Test') {
            steps {
                bat 'npm test'
            }
        }
        stage('Build') {
            steps {
                echo 'Bravo, déploiement réussi !'
            }
        }
    }
}