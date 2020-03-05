pipeline {
    agent {
        docker { 
            image 'jenkins:3-alpine' 
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'pwd'
                sh '/var/lib/jenkins/workspace/bash_test/hello_world.sh'
            }
        }
    }
}
