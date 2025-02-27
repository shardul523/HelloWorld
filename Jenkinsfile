pipeline {
	agent any

	stages {
		stage('Checkout Code') {
			steps {
				echo "Pulling code from Github..."
			}
		}
		
		stage('Build') {
			steps {
				echo 'Building the project...'
			}
		}

		stage('Test') {
			steps {
				echo 'Running tests...'
			}
		}

		stage('Deploy') {
			steps {
				echo 'Deploying application...'
			}
		}
	}

	post {
		success {
			echo 'Build and deployment successful'
		}
		failure {
			echo 'Build failed'
		}
	}

}
