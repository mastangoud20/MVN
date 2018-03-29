pipeline {
     agent any
	
	tools {
        maven 'M2_HOME'
        jdk 'jdk1.8'
    }
	
    stages {
        stage('Clean') {
            steps {
                
		    echo "cleaning"
		    bat "mvn clean"
            }
        }
	    
	            stage('Install') {
            steps {
                
		    echo "installing"
		    bat "mvn install"
            }
        }
	    
	            stage('Compile') {
            steps {
                
		    echo "Compile"
		    bat "mvn compile"
		    
		       }
        }
		    
	        stage('Build') {
            steps {
                
		    echo "Packaging"
		    bat "mvn Package"
         
            }
        }
	
			
	}

}
		

	
