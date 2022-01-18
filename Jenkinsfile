pipeline{
agent any
  stages{
    stage("checkout"){
    steps{
      script{
       checkout scm
       }
     }
    }
    stage("present working directory"){
    steps{
      script{
       sh 'pwd'
       }
     }
    }
    
    stage("Execuation of the script"){
    steps{
      script{
       sh './script.sh'
       }
     }
    }
  } 
}
