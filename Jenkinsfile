node{
stage('SCM Checkout'){
 
git 'https://github.com/chandrashekhar97/TestJenkins'
}
stage('Compile-Package'){
  //Get maven home path
   def mvmHome=tool name: '', type: 'maven'
  sh "${mvmHome}/bin/mvn package"
}
}
