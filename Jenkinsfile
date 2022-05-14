pipeline {
 
  agent any
  
  stages {
   
    stage("Initialize") {
      
      steps {
        echo "Installing deps"
        sh 'npm i'
      }
      
    }
  
    stage("Build") {
      
      steps {
        echo "Application building"
        sh 'npm run build'
      }
      
    }
    
    stage("Test") {
      
      steps {
        echo "Application testing"
      }
      
    }
    
    stage("Publish") {
      
      steps {
        echo "Application publishing"
      }
      
    }
  }
  
}
