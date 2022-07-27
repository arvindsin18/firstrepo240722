pipeline{
    agent any
  
      stages{
        
        stage("build"){
          steps{
            echo 'Building module'
                }
                      }
        stage("Test"){
          steps{
            echo 'Testing module'
                }
                      }
        stage("Deploy"){
          steps{
            echo 'Deploying module'
                }
                      }
          stage("Checking poll again "build 17"){
          steps{
            echo 'Sucsessfully triggered by poll'
                }
                      }
            
         
      
            }
        }
