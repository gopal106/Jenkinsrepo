pipeline
{ 
  
   agent any

   stages
   {
   
     stage('Build') 
     { 
        steps 
	{ 
          sh 'make check || true' 
          junit '**/target/*.xml'
        }
     }
     
     stage('Test') 
     { 
        steps 
	{ 
          bat 'echo "testing application..."'
        }
      }

         stage("Deploy application") 
	 { 
         steps 
	 { 
          bat 'echo "deploying application..."'
         }

     }
  
   	}

   }
