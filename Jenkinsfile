node {

stage("checkout")
  {
    
   git "https://github.com/yellanurmadhu/TestMavenRepo1.git"
  }
  
stage("compile")
  {
  def mvnHOME = tool name: 'apache-maven-3.6.0-bin', type: 'maven'
    sh ="${mvnHOME}/bin/mvn package"
}
}
