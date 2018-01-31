pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        checkout scm
        dir('kubeDemo/script') {
                  sh 'pwd'
          
                  sh '''
                  cd /var/lib/jenkins/workspace/kubeDemo_master-T5WCNAFFAGLTBLHBKLISKXINTVQSKIVQBF5MPWR6JW5XKPZ666NQ/kubeDemo/script/
                  ./example.sh
                  '''
                }
        
      }
    }
    
  }
}
