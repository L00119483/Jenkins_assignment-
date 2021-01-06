node{
  stage('checkout'){
    git 'https://github.com/L00119483/Jenkins_assignment-'
  }
  stage('compile'){
    
   def mvnHome = tool name: 'maven5', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
