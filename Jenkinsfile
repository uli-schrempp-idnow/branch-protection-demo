pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Bob the Baumeister ..."
            }
        }
        stage('Environment') {
            steps {
                sh "printenv"
            }
        }
        stage('Library Checks') {
            steps {
                prJiraCrosscheck()
            }
        }
    }
}
