pipeline {
     agent any

	stages {
		stage ( 'Compile Stage') {

		steps {
			
		 step {
			
			vn clean compile
			
			}
				
		  }
		}
	}	
		

		stage ( 'Testing Stage') {

		steps {
			withMaven(maven : 'maven-3.5.2') {
			mvn test
				
			}
		   }		
			
		}

			stage ( 'Deploy Stage') {

		step {
			withMaven(maven : 'maven-3.5.2') {
			mvn deploy
				
			}
		   }		
			
		}

           }
		

	
