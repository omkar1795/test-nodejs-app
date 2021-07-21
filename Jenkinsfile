pipeline {   
   agent any

   stages {
   
     stage('Cloning') { 
        steps { 
           sh 'echo "This is cloning stage"' 
        }
     }
     stage('Scan') { 
        steps { 
           sh 'echo "Scanning application code using sonarqube"'
        }
      }
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }
     stage("Deploy application") { 
         steps { 
           sh 'echo "deploying nodejs application..."'
         }
     } 
  }

}
