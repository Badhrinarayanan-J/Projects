pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building app...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                sh 'cd python && bash deploy.sh'
            }
        }
    }
}
