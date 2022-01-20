pipeline
{ 
  
   agent any

   stages
   {
   
     stage("Build") 
     { 
        steps 
	{ 
           bat 'echo"build the last application"'
        }
     }
     
     stage('Test') 
     { 
        steps 
	{ 
           bat 'echo "testing the last application..."'
        }
      }

         stage("Deploy application") 
	 { 
         steps 
	 { 
           bat 'echo "deploying the last application..."'
         }

     }
  
   	}

   }
