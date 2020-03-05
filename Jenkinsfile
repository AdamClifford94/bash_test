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
                sh 'chmod +x hello_world.sh'
                sh './hello_world.sh'
            }
        }
    }
}
