pipeline {
  agent any
    
  tools {NodeJS "node"}
    
  stages {
        
    stage('Git') {
      steps {
        git "https://github.com/NIK8H/master.git"
      }
    }
     
    stage("Build") {
      steps {
        sh "npm install"
        sh "gulp webpack"
      }
    }  
    }
  }
