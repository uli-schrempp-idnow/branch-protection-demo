pipeline {
    agent any

    stages {
        
        stage('Check') {
            steps {
                publishChecks name: 'dummy', summary: 'lore ipsum', text: 'Das ist der Text', title: 'Dummy Check'
            }
        }
    }
}
