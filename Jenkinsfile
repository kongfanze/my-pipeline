pipeline {
  agent none
  stages {
    stage('test') {
      agent {label 'sip'}
      steps {
        sh 'echo hello world'
      }
    }

  }
}
