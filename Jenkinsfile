Pipeline {
     agent any

	stages {
		stage ( 'Compile Stage'){

		steps{
			withMaven(maven : 'maven-3.5.2'){
			sh 'mvn clean compile'
				
			}
		   }		
			
		}

		stage ( 'Testing Stage'){

		steps{
			withMaven(maven : 'maven-3.5.2'){
			sh 'mvn test'
				
			}
		   }		
			
		}

			stage ( 'Deploy Stage'){

		steps{
			withMaven(maven : 'maven-3.5.2'){
			sh 'mvn deploy'
				
			}
		   }		
			
		}

}

}	