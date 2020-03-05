pipeline {
    agent {
        docker { 
            image 'node:7-alpine' 
            args '-u root:root'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh './hello_world.sh'
            }
        }
    }
}
