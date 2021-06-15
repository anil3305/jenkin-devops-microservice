pipeline {
	agent any
	//agent { docker { image 'maven:3.6.3'} }
	stages {
		stage('Build'){
			steps{
				//sh 'mvn --version'
				echo "Build"
			}
		}
		stage('Test'){
			steps{
				echo "Test"
			}
		}
		stage('Inegration Test'){
			steps{
				echo "Integration Test"
			}
		}
	}
	post {
		always {
			echo "i am awsome, run always"
		}
		success {
			echo "print if i am successful"
		}
		failure {
			echo "print if i fail"
		}

	}
}