pipeline {
    agent any

    stages {
        stage('Git-clone') {
            steps {
               git branch: 'main', changelog: false, poll: false, url: 'https://github.com/tngraceenough/ci-cd-test'
            }
        }
        stage('Install apache'){
            steps {
            sh 'sudo apt install apache2 -y'
        }
        }
        stage('Deploy Code') {
            steps {
            sh 'sudo apt install apache2 -y'   
            }
        }
        }
    }
