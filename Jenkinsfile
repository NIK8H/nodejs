pipeline {
  agent any
    
  tools {nodejs "nodejs"}
    
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/NIK8H/master.git'
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }  
    }
  }
}
