pipeline {
  agent any
  stages {
    stage('master') {
      steps {
        sh 'echo "hello word!"'
        sh '''cnpm install
echo "npm install end..."'''
        sh '''npm run build
echo "build end ..."'''
      }
    }
  }
}