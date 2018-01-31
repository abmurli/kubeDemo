pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        checkout scm
        dir('kubeDemo/script') {
                  sh 'pwd'
                  sh 'chmod 777 /var/lib/jenkins/workspace/kubeDemo_master-T5WCNAFFAGLTBLHBKLISKXINTVQSKIVQBF5MPWR6JW5XKPZ666NQ/kubeDemo/script/example.sh'
                  sh '/var/lib/jenkins/workspace/kubeDemo_master-T5WCNAFFAGLTBLHBKLISKXINTVQSKIVQBF5MPWR6JW5XKPZ666NQ/kubeDemo/script/./example.sh'
                }
        
      }
    }
    
  }
}
