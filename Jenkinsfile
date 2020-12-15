
pipeline{
  stages {
	stage('Build')
	{
		steps {
			echo "Building the project"
			sh './gradlew build --no-daemon'
			archiveArtifacts artifacts: 'dist/trainSchedule.zip'
		}
	}
  }
}
