pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        checkout scm
        dir('kubeDemo/script') {
                  sh 'pwd'
                  sh 'chmod 777 example.sh'
                  sh './example.sh'
                }
        
      }
    }
    
  }
}
