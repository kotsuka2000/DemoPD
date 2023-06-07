pipeline {
	agent any
	stages {
		stage('One') {
			steps {
				echo 'Hi, this is Soumitra from roytuts'
			}
		}
	
		stage('Build') {
            steps {
                sh './gradlew build'
            }
        }

		stage('Three') {
			steps {
				echo 'Build done'
			}
		}	
        
        stage('archive') {
			steps {
				archiveArtifacts(artifacts: '**/*.jar', followSymlinks: false)
			}
		}		

	}
}