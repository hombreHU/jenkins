pipeline {
  agent any
  stages {
    stage('delete ') {
      steps {
        sh '/Data/jenkins/kubectl delete -f /Data/jenkins/jira-service.yaml'
      }
    }
  }
}