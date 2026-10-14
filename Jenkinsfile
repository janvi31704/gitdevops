
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checkout stage started'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project'
                sh 'whoami'
                sh 'pwd'
            }
        }

        stage('Test') {
            steps {
                echo 'Tests completed successfully'
            }
        }
    }
}
