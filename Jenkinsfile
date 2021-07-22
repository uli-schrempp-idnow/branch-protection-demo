pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Bob the Baumeister ..."
            }
        }
        stage('Library Checks') {
            steps {
                prJiraCrosscheck()
            }
        }
        stage('Environment') {
            steps {
                sh "printenv"
            }
        }
    }
}
