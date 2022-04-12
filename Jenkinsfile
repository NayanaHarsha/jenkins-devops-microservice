//scripted file
// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
//   stage('Integration Tests') {
// 		echo "Test"
// 	}
// }

//Declarative pilelie

pipeline {
	agent {
		docker [image 'maven:3.6.3']
		}
	
	stages {
		stage('Build') {
			steps {
				echo "mvn --version"
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Tests') {
			steps {
				echo "Test"
			}
		}
	}
	post {
		always {
			echo "Always run successfully"
		}
		success {
			echo "Always run on success"
		}
		failure {
			echo "Always run on failure"
		}
	}
}