pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Code checkout completed'
            }
        }

        stage('Build') {
            steps {
                sh 'python3 app.py'
            }
        }

        stage('System Info') {
            steps {
                sh 'whoami'
                sh 'hostname'
                sh 'pwd'
            }
        }
    }
}
#123456




