pipeline {
  agent any
  stages {
  stage('Build') {
    steps {
      checkout scm
      sh 'pwd'
      sh './example.sh'
              }
      
    }
    stage('inside Script') {
      steps {
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
