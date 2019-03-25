pipeline {
  agent {
    node {
      label 'localhost'
    }

  }
  stages {
    stage('delete ') {
      steps {
        sh 'kubectl delete -f /Users/hombre/Desktop/docker/sjira/kjira/jira-service.yaml'
      }
    }
  }
}