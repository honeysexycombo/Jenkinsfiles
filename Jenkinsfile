pipeline {
  agent {
    label "main"
  }
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}