pipeline {
    agent {
        docker { 
            image 'maven:3-alpine' 
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
