pipeline {
    agent any

    stages {
        stage('one') {
            steps {
                echo 'Sleeping for 2 seconds...'
                sh 'sleep 2'
            }
        }

        stage('two') {
            steps {
                echo 'Sleeping for 2 seconds...'
                sh 'sleep 2'
            }
        }

        stage('three') {
            steps {
                echo 'Sleeping for 2 seconds...'
                sh 'sleep 2'
            }
        }  
    }

    post {
        success {
            echo '✅ Pipeline executed successfully!'
        }
        failure {
            echo '❌ Pipeline failed!'
        }
    }
}
