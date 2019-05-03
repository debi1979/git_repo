pipeline{
	agent any
		stages{
			stage('one'){
				steps {
					echo 'Hi, this my 1st groovy script'
				}
			}
			stage('Two') {
				steps  {
					input('Do you want to proceed?')
				}
			}
			stage('Three') {
				when {
			             not {
						branch "master"
				     }
				}
				steps {
					echo 'Hello jenkins pipeline'
				}
			}
		}
}
	 
			 	 				
