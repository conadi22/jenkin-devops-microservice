pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
	}
	post {
		always {
			echo 'Im awsome. I run always!'
		}
		success {
			echo 'I run wen success'
		}
		failure {
			echo 'I run when failure '
		}
	}
}
