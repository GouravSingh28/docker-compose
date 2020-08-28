pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        tool(name: 'nodejs-14', type: 'nodejs')
      }
    }

    stage('install dependency') {
      steps {
        sh 'npm install -g'
      }
    }

  }
}