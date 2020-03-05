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
                sh 'pwd'
                sh 'chmod +x /var/lib/jenkins/workspace/bash_test/hello_world.sh'
                sh '/var/lib/jenkins/workspace/bash_test/hello_world.sh'
            }
        }
    }
}
