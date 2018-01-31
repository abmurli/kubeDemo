pipeline {
  agent any
  stages {
  stage('Build') {
    steps {
      checkout scm
      sh 'pwd'
      sh 'chmod 777 example.sh'
      sh './example.sh'
              }
      
    }
    stage('inside Script') {
      steps {
                  sh 'pwd'
                  sh 'ls /var/lib/jenkins/workspace/kubeDemo_master-T5WCNAFFAGLTBLHBKLISKXINTVQSKIVQBF5MPWR6JW5XKPZ666NQ'
                  sh '''
                  cd /var/lib/jenkins/workspace/kubeDemo_master-T5WCNAFFAGLTBLHBKLISKXINTVQSKIVQBF5MPWR6JW5XKPZ666NQ/script/
                  chmod 777 example.sh
                  ./example.sh
                 '''
      }
    }
}
}
