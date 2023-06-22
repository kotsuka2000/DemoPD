pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				// Change file permisson
                sh "chmod +x -R ./jenkins"
                // Run shell script
                sh "./jenkins/script/helloworld.sh"
			}
		}       
 
	}
}