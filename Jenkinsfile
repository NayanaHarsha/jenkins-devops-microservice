pipeline {
	agent any
stages{
	stage('Build'){
		steps{
			echo 'hello world'
		}
	}
	stage('Qa'){
		steps{
			echo 'hello'
			script {
				def test = 2 + 2 > 3 ? 'cool' :' notcool'
			}
		}
	}
	stage('prod'){
		steps{
			echo 'hello-world'
		}
	}
}
}
