pipeline {
  agent any
  stages {
    stage('master') {
      steps {
        sh 'echo "hello word!"'
        sh 'npm install'
      }
    }
    stage('Build') {
      steps {
        sh 'npm run build'
      }
    }
  }
}