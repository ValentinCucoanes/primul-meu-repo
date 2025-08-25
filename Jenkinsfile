pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                echo 'Installing...'
                sh 'npm install'
            }
        }

        stage('Run Tests') {
            steps {
                echo 'Testing...'
                sh 'npm test'
            }
        }
    }
}

