pipeline {
  agent any
  stages {
    stage('CheckoutRepo') {
      steps {
        jiraIssueSelector()
      }
    }
  }
}