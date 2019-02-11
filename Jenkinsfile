node{
stage('SCM Checkout'){
git 'https://github.com/chandrashekhar97/TestJenkins'
}
stage(Compile-Package){
sh 'mvn package'
}
}
