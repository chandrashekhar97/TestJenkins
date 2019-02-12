node{
stage('SCM Checkout'){
 
git 'https://github.com/chandrashekhar97/TestJenkins'
}
stage('Compile-Package'){
  //Get maven home path
   def MAVEN_HOME=tool name: 'maven3', type: 'maven'
  sh "${MAVEN_HOME}/bin/mvn package"
}
}
