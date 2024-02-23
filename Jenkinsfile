 pipeline{
 agent any
 stages{
 stage("clonig the url"){
 steps{
 script{
  sh'git clone https://github.com/venkat0007/helm-frontend.git -b main'
  }
  }
  }
  stage("deploying the application "){
  steps{
  script{
   sh 'helm upgrade --install frontend . --values values-devtest.yaml'
   }
   }
   }
   }
   }
