pipeline {
		agent { 
			docker {
				image 'maven:3.6.3'
			}
			}
		stages {
				stage('Build') {
						steps {
								echo "Hello World"
								echo "maven version: ${maven.version}"
						}
				}
		}
}