node('docker') {
    checkout scm
    stage('Build') {
        docker.image('python:3.8.3').inside {
            sh 'python --version'
        }
    }
}