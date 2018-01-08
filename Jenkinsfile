pipeline {
  agent none
  stages {
    stage('error') {
      steps {
        pwd()
        fileExists 'A2.txt'
        sleep 1
      }
    }
  }
}