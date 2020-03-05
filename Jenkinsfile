pipeline {
    agent {
        docker { 
            image 'node:7-alpine' 
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'whoami'
                sh './hello_world.sh'
            }
        }
    }
}
