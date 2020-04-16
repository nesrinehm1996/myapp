node{
   stage('SCM Checkout'){
      git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-Package'){
      //get maven home path 
      def mvnHome = tool name: 'maven', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }

}
