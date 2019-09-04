pipeline {
  agent any
  stages {
    stage('instll ') {
      steps {
        sh 'echo "hello word!"'
        sh '''
#!/bin/sh -l npm install'''
      }
    }
    stage('Build') {
      steps {
        sh '''
#!/bin/sh -l node run build'''
      }
    }
  }
}