pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building  nguaa-vehicle-nickname'
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
