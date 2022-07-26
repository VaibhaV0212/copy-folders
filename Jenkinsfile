pipeline{
  agent any
  environment{
    REPO_NAME = "copy-folders"
  }
  
  stages {
    stage('Check fields'){
      steps{
        script{
          if env.SOURCE.trim().isEmpty()){
            error "Source name cannot be empty."
          }
        }
      }
      
      stage('Copy'){
        steps{
          script{
            
          }
        }
      }
      
      
    }
    
    
    




}
