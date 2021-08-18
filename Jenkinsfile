pipeline{
	agent any
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
			stage('build groovy script'){
			   steps{
				script{
					grrovy.buildApp()
				}
			   }
			}
			stage('deploye groovy script'){
			   steps{
				script{
					grrovy.deployeApp()
					}
				}
			}
		  }
		}
