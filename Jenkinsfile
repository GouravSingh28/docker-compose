pipeline {
  agent any
  stages {
    stage('Build') {
      tools {
        maven 'maven-3.6.3'
      }
      steps {
        sh 'mvn -version'
      }
    }

  }
}