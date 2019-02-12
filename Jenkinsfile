node{
stage('SCM Checkout'){
 
git 'https://github.com/chandrashekhar97/TestJenkins'
}
stage('Compile-Package'){
  //Get maven home path
   def mvmHome=tool name: 'maven3', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}
}
