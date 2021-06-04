node{
  stage('SCM Checkout'){
    git 'https://github.com/chakri8/project1'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: 'maven_home', type: 'maven'
    sh "${mvnHome}/bin/mvn clean install package"
  }

}
