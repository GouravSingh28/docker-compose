pipeline {
  agent any
    

  stages {    
    
            
    stage('Install dependencies') {
      steps {
	    tool name: 'nodejs-14', type: 'nodejs'
        sh 'npm --version'
		
      }
    }     
               
  }
}
