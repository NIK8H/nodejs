pipeline {
  agent any
    nodejs('NodeJS') {
    // some block
}
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'gulp webpack'
            }
        }
    }
}
