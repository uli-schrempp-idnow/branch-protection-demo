pipeline {
    agent any

    stages {
        stage('Branch-Name-Check') {
            steps {
                publishChecks name: 'Branch Name Check XXX', summary: 'Verifies the Branch-Name contains a JIRA-Ticket', 
                      text: 'Verifies the Branch-Name contains a JIRA-Ticket', title: 'Branch Name Check'
            }
        }
        stage('Commit-Messages-Check') {
            steps {
                publishChecks name: 'Commit Messages Check XXX', summary: 'Verifies each Commit-Meesage contains a JIRA-Ticket', 
                      text: 'Verifies each Commit-Meesage contains a JIRA-Ticket', title: 'Commit-Message Check '
            }
        }
        stage('PR-Name-Check') {
            steps {
                publishChecks name: 'PR Name Check XXX', summary: 'Verifies the PR-Name contains a JIRA-Ticket', 
                      text: 'Verifies the PR-Name contains a JIRA-Ticket', title: 'PR Name Check'
            }
        }
    }
}
