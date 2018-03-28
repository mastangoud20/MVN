pipeline {
     agent any
	

	stages {
		stage ('Compile Stage') {

		steps {
					
			mvn clean compile
			
			}
				
		  }
		
	
		stage ('Testing Stage') {

		steps {
			
			sh 'mvn test'
				
			}
		   }		
			
		

			stage ('Deploy Stage') {

		steps {
			
			sh 'mvn deploy'
				
			}
		   }		
		}	
	}
		

	
