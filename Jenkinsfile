node{
   stage('SCM Checkout'){
     git 'https://github.com/sarathplutor/sampleapp'
   }
   stage('Compile-Package'){
     def mvnHome = tool name: 'mavaTest', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }
      

}
