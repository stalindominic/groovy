pipeline{
	agent {
			label any
		  }
		  stages{
				stage('Invoke grovy script'){
					steps{
						script{
						groovy = load 'script.groovy'
						}
					}
				}
				stage('compile groovy script'){
					steps{
						script{
						groovy.compileApp()
					}
				}
			}
			stage('test groovy script'){
			
				steps {
					script {
					grrovy.testApp()
					}
				}
			}
		}
		
	}
