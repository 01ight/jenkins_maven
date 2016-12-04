node {
  def mvnHome = tool 'M3'
 
   stage 'mvn package'
       env.PATH = "${mvnHome}/bin:${env.PATH}"
       sh 'mvn -B verify'	
}
