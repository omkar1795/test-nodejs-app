pipeline {   
   agent any

   stages {
   
     stage('Cloning') { 
        steps { 
           sh 'echo "This is cloning stage" ' 
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
