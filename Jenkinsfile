pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
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
  environment {
    docker = '#!/bin/bash'
  }
}