pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'sudo ./hello_world.sh'
            }
        }
    }
}
