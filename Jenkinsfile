pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'npm start'
      }
    }
    stage('test') {
      steps {
        sh 'npm test --wachtchAll=false'
      }
    }
  }
}