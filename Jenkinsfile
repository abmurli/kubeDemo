pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        checkout scm
        sh 'chmod 777 example.sh'
        sh './example.sh'
      }
    }
    
  }
}
