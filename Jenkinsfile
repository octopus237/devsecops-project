pipeline {
  agent {
      label 'agent1' 
      docker {
          image 'maven:3-alpine'
      }
  }
  
  stages {
      stage('Build'){
          steps{
              sh 'mvn package'
          }
      }
  }
      
      
    
}
