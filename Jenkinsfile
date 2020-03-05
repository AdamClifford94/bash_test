pipeline {
    agent {
        docker { 
            image 'node:7-alpine' 
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'pwd'
                sh './hello_world.sh'
            }
        }
    }
}
