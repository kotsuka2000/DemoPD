pipeline {
	agent any
	stages {
		stage('One') {
			steps {
				echo 'Hi, this is Soumitra from roytuts'
			}
		}
		
		stage('Two') {
			steps {
				input('Do you want to proceed?')
			}
		}
		
		stage('Build') {
            steps {
                sh './gradlew build'
		
		stage('Three') {
			steps {
				echo 'Finished'
			}
		}		
	}
}