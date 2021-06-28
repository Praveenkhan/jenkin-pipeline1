pipeline {
    agent { docker { image 'node:14-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
		echo 'building the application'
            }
       }
   stage('deploy') {
            steps {
                echo 'deploying the application'
            }
       }
	stage('test') {
            steps {
                
                echo 'testing the application'
            }
       }


    }


}
