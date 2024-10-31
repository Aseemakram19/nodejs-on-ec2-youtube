pipeline {
    agent any

    stages {
        stage('Stage-1 , clean ws') {
            steps {
                cleanWs()
            }
        }
        stage('Stage-2 , Git clone scm') {
            steps {
                 git 'https://github.com/Aseemakram19/nodejs-on-ec2-youtube.git'
            }
            }
        }
        stage('Stage-3 , npm install') {
            steps {
                sh 'npm install'
            }
        }                
    }
}
