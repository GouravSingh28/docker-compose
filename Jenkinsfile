pipeline {
    agent any

    stages {
        stage('Build') {
   tools {
          nodejs 'nodejs-14'
        //maven 'maven3_0_5'
        }
              steps {
                sh 'npm --version'
            }
        }
    }
}