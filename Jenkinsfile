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
        env.NODEJS_HOME = "${tool 'nodejs-14'}"
        env.PATH="${env.NODEJS_HOME}/bin:${env.PATH}"
        sh 'npm --version'
      }
    }

  }
}