pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'default') {
                    sh 'mvn clean compile'
                }
            }
        }
	}
	
}

   
    
