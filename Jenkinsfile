pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building  nguaa-vehicle-nickname'
				input(message: 'Do you want to continue with Dev Deployment ?', id: '1', ok: 'OK', submitter: 'jenkins', submitterParameter: 'jenkins')
				build 'nguaa-vehicle-nickname'
				echo 'Build complete'
            }
        }
        stage('Dev Deployment') {
            steps {
                echo 'Build Dev Deployment Steps'
            }	
        }
        stage('test Deployment') {
            steps {
                echo 'Build test Deployment Steps'
            }	
        }
    }	
}
