//Jenkinsfile (Declarative Pipeline)

/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.4-eclipse-temurin-17-alpine' } }
    stages {
	stage('custom_stage') {
	    steps {
		sh 'echo custom_step'
	    }
	}
        stage('build') {
            steps {
                sh 'mvn --version'
		sh 'echo kacsa'
            }
        }
    }
}

