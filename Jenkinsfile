pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'india'
      }
    }

    stage('compile') {
      parallel {
        stage('compile') {
          steps {
            echo 'chutiyapa'
          }
        }

        stage('compile2') {
          steps {
            echo 'bihuhahhaha'
          }
        }

      }
    }

  }
}