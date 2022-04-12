pipeline {
		agent { 
			docker {
				image "node:8-alpine"
			}
			}
		stages {
				stage('Build') {
						steps {
								echo "Hello World"
								echo "node version: ${node.version}"
						}
				}
		}
}