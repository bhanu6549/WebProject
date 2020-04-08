
node{

 
stage('SCM Checkout'){
 
git 'https://github.com/bhanu6549/Jenkins'

 
}

 
stage('Compile Package'){

 
def mvnHome= tool name: 'Maven 3', type: 'maven'

 
sh "${mvnHome}/bin/mvn package"

 
}
  mail bcc: '', body: 'welcome to jenkins', cc: '', from: '', replyTo: '', subject: 'Jenkins', to: 'bhanumindtree2020@gmail.com'
 

 
}
