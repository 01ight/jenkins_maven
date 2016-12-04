node {
  def mvnHome = tool 'M3'
 
   stage 'mvn package'
      sh "${mvnHome}/bin/mvn clean package"
      echo 'mvn task finished'	
}
