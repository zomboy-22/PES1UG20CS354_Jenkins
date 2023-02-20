pipeline{
  agent any
  
  stages{
    stage('Build'){
      steps {
        sh 'g++ -o PES1UG20CS354-1 hello_2.cpp'
      }
    }
    
    stage('Test'){
      steps {
        sh './Unknown'
      }
    }
    
    stage('Deploy') {
      steps{
        echo 'Deployment Successful'
      }
    }
  }
  
  post{
    success{
      echo 'Pipeline Finished'
    }
    
    failure{
      echo 'Pipeline Failed'
    }
  }
}
