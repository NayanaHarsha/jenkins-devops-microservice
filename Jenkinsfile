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
		steps('Build'){
			echo "Build"
		}
			steps('Test'){
			echo "test"
		}
			steps('Intergration tests'){
			echo "Tests"
		}
	}
}

