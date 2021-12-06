pipeline {
	//agent any
	//agent  {
	//	docker {
	//		image 'maven:3.6.3'
	//	}
	//}
	stages {
		stage('Build') {
			steps {
				//sh 'docker version'
                sh 'mvn --version'
                //sh 'java -version'
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
