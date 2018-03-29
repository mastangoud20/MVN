pipeline {
     agent any
	
	
    stages {
        stage('Build') {
            steps {
                  def mvnHome = tool 'M2'
                  sh "${mvnHome}/bin/mvn clean package"
            }
        }
	
			
	}

}
		

	
