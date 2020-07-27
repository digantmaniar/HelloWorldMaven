pipeline {
	agent any
	tools {
        maven 'maven-3.6.3' 
    }
	stages {
		
		stage('Checkout Source') {
			steps {
				echo 'Check out the project'
			    echo "Branch Name : ${env.BRANCH_NAME}"
				checkout scm  
				}
			}
		
		stage('Build') {
			steps {
				echo 'Building project'
			    bat "mvn clean install"
				  
				}
			}
		}
	}
