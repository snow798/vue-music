pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'echo "hello word!"'
        sh '''npm install
echo "npm install end..."'''
        sh '''npm run build
echo "build end ..."'''
      }
    }
  }
}