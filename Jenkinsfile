node{
    git branch:"main", credentialid:'github_c', url: 'https://github.com/L00119483/Jenkins_assignment-'
  }
  stage('compile'){
   sh 'mvn package'

   def mvnHome = tool name: 'maven5', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
