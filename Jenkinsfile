node {
    def workspace = pwd() 
	
   stage 'mvn package'
      echo  ${workspace}
      sh 'mvn clean package'
      echo 'mvn task finished'	
}
