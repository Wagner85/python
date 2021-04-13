pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        sh 'ping 8.8.8.8 -c4'
        sh 'ping 8.8.8.8 -c2'
      }
    }
stage('2') {
      steps {
        sh 'ping 8.8.8.8 -c4'
        sh 'ping 8.8.8.8 -c2'
      }
    }
  }
}
