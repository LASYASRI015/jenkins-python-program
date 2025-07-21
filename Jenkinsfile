pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                echo "Compiled Successfully"
            }
        }

        stage('Junit') {
            steps {
                echo "JUnit test passed Successfully"
            }
        }

        stage('Quality check') {
            steps {
                echo "Quality check passed successfullly"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deployed Successfully"
            }
        }
    }

    post {
        always {
            echo "This will always run"
        }
        success {
            echo "this will run on success"
        }
        failure {
            echo "This will run on failure"
        }
        unstable {
            echo "this will run only if the run is marked as unstable"
        }
        changed {
            echo "pipe line chnaged"
        }
    }
}

