pipeline{
  agent any
    stages {
      stage ('present'){
        steps{
         pwd
        }
      }
      stage ('clean'){
        steps{
          sh "mvn clean" 
              }
                      }
      stage ( 'test'){
          steps {
              sh "mvn test"
                }    }
      stage ( ' deploy'){
          steps{
                sh "mvn package"
          }}    
          
            }
          }
