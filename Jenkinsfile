pipeline {
    agent {
        docker { 
            image 'node:7-alpine' 
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'su jenkins'
                sh 'pwd'
                sh '/var/lib/jenkins/workspace/bash_test/hello_world.sh'
            }
        }
    }
}
