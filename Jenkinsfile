pipeline {
	agent any
	stages {
		stage('Build Images'){
			steps {
				sh "./scripts/build.sh"
			}
		}
		stage('Run Containers'){
			steps {
				sh "./scripts/run.sh"
			}
		}
	}
}
