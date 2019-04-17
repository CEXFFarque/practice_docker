pipeline {
		environment {
			DOCKER = credentials('docker-hub')
		}
	agent any
	stages {
// Building your Test Images
		stage('BUILD') {
			steps {
				echo 'This is the Build Stage'
			}
		}
// Deploying your Software
		stage('DEPLOY') {
			steps {
				echo 'This is the Deploy Stage'
			}
		}
// JUnit reports and artifacts saving
		stage('REPORTS') {
			steps {
				echo 'This is the Reports Stage'
			}
		}
// Doing containers clean-up to avoid conflicts in future builds
		stage('CLEAN-UP') {
			steps {
				echo 'This is the CLEAN-UP Stage'
			}
		}
	}
}

