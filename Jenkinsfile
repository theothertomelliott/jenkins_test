pipeline {
    agent any

    tools {
        go "1.24"
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'go version'
            }
        }
        stage('Test') {
            steps {
                echo 'Test test..'
            }
        }
        stage('Test2') {
            steps {
                echo 'Test test..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying once again....'
            }
        }
    }
}