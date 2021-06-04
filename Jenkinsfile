node{
  stage( 'SCM Checkout'){
  git 'https://github.com/chakri8/project1'
  }
  stage('Compile-Package'){
  sh 'mvn clean install package'
  }

}
