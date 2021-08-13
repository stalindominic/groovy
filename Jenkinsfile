pipeline{
	agent {
			label any
		  }
		  stages{
				stage('Invoke grovy script'){
					steps{
						script{
						groovy=load "script.groovy"
						}
					}
				}
			}
		}
