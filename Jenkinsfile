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