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
