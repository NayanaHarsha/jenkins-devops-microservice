pipeline {
		agent any {
		stages {
				stage('Build') {
						steps {
							  echo "Build"
								echo "$PATH"
								echo "$HOME"
								echo "$BUILD_NUMBER - $env.BUILD_NUMBER"
								echo "$env.BUILD_ID"
								echo  "$JOB_NAME - $env.JOB_NAME"
								echo "$BUILD_URL - $env.BUILD_URL"
								echo "$BUILD_TAG - $env.BUILD_TAG"
								echo "Hello World"
								echo "maven version: ${maven.version}"
						}
						stage('Test') {
								steps {
										echo "Test"
								}
						}
						stage
						stage('Deploy') {
								steps {
										echo "Deploy"
								}
						}
				}
		}
}