pipeline {
    agent {
        label 'ibnqa003401.bpc.broadcom.net'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'docker ps -a'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'docker images'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
