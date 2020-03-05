pipeline {
    agent {
        docker { 
            image 'jenkins' 
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
