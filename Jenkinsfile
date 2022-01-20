pipeline
{ 
  
   agent any

   stages
   {
   
     stage('Build') 
     { 
        steps 
	{ 
         bat 'echo "building application..."'
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
