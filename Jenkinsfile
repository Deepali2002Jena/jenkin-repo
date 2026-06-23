pipeline {
    agent any 
    environment{
        shyam= 'redhat'
    }
	parameters {
    	string(name: 'person', defaultValue: 'ram mishra', description: 'how r u')
	}
    
    stages {  
        stage('run linux command') {
            steps {
                sh 'date'
                sh 'echo $shyam'				
            }
		}
		stage('check parameter') {
            steps {
                sh 'echo $person'			
            }
		}
	}
}
