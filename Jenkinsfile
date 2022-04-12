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

pipeline{
	agent any
	stages{
		stage('Build'){
			steps{
					echo "Build"
			}
		
		}
			stage('Test'){
				steps{
			     echo "test"
				}
		}
			stage('Integration Tests'){
				steps{
			     echo "Integration test"
				}
		}
	}
}

