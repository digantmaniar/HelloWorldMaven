pipeline {
	agent any
	tools {
        maven 'maven-3.6.3' 
    }
	stages {
		stage('Build') {
			steps {
				echo 'Building project'
			    bat "mvn clean install"
				  
				}
			}
		}
	}
