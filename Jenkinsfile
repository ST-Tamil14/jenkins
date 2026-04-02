pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Run Python Code') {
            steps {
                bat 'python max.py'
            }
        }

        stage('Done') {
            steps {
                echo 'Pipeline completed successfully!'
            }
        }
    }
}
