pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('master') {
      steps {
        sh 'echo "hello word!"'
        sh '''
#!/bin/bash -ilex npm install'''
      }
    }
    stage('Build') {
      steps {
        sh 'node run build'
      }
    }
  }
}