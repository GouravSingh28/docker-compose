pipeline {
    agent any

    stages {
        stage('Build') {
   tools {
          nodejs 'nodejs13'
        //maven 'maven3_0_5'
        }
              steps {
                sh 'npm --version'
            }
        }
    }
}