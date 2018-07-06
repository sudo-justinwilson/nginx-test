pipeline {
//    agent { docker { image 'python:3.5.1' } }
    agent { docker { image 'nginx:alpine' } }
    stages {
        stage('build') {
            steps {
//                sh 'python --version'
                sh test.sh
            }
        }
    }
}
