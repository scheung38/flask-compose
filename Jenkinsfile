pipeline {
    agent { docker  'python:3.6.4' }

        stage('build') {
            steps {
                sh 'python --version'
            }
        }

        stage('print') {
            steps {
                sh 'ls -al'
            }
        }

}


/*
node('docker') {
    checkout scm
    stage('Build') {
        docker.image('python:3.6.4').inside {
            sh 'python --version'
        }
    }
}
*/
