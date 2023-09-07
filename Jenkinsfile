pipeline {
	agent {docker {image 'maven:3.6.3'}}
	stages {
		stage ('Build') {
			steps {
				echo "Build"
				sh 'mvn --version'
			}
		}
		stage ('Test') {
			steps {
				echo "Test"
			}
		}
		
	}	
}
