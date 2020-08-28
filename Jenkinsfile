pipeline {
  agent any
  stages {
    stage('Build') {
      tools {
        nodejs 'nodejs-14'
      }
      steps {
        sh 'npm --version'
      }
    }

    stage('compile') {
      steps {
        sh 'npm install -g'
      }
    }

  }
}