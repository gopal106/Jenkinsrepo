<<<<<<< HEAD
pipeline
{ 
  
   agent any

   stages
   {
   
     stage('Install Dependencies') 
     { 
        steps 
	{ 
           sh 'npm install' 
        }
     }
     
     stage('Test') 
     { 
        steps 
	{ 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") 
	 { 
         steps 
	 { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
=======
node
{ 
  stage ('SCM checkout')
  {
      git 'https://github.com/gopal106/Jenkinsrepo.git'
  }
   stage ('Compile-Package')
  {
      def MVN_Home = tool name: 'MAVEN_HOME', type: 'maven'
      sh "${MVN_Home}/bin/mvn package"
 }       

}
>>>>>>> 4e558838a173234be95e02d109f519ed8ae16f92
