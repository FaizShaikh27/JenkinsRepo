pipeline{
	agent any
	stages{
		stage('Hello'){
			steps{
				echo 'Hello World'
				echo 'Testing the scripted jenkinsfile'
				bat 'java-version'
			}
		}
		stage('Compile'){
			steps{
				echo 'Compiling java code'
				bat 'javac Main.java'
				bat 'java Main'
			}
		}
	}
}