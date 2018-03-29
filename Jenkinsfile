pipeline {
     agent any
	
	tools {
        maven 'M2_HOME'
        jdk 'jdk1.8'
    }
	
    stages {
        stage('Build') {
            steps {
                
		    echo "building"
		    bat "mvn clean"
            }
        }
	
			
	}

}
		

	
