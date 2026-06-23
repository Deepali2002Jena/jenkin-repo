pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
		stage('run linux command') {
            steps {
                sh 'date'
				sh 'cal'
            }
		}
		stage('run linux command') {
            steps {
                sh 'echo $BUILD_ID'
				sh 'cal'
            }
        }
    }
}
