pipeline {
	agent any
	stages {
		stage('One') {
			steps {
				// Change file permisson
                sh "chmod +x -R ./jenkins"
                // Run shell script
                sh "./jenkins/script/scripted_pipeline_ex_2.sh"
			}
		}       
 
	}
}