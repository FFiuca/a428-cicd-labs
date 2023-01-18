node{
    agent {
        docker {
            image 'node:lts-buster-slim'
            args '-p 3000:3000'
        }
    }
    stages{
        stage('install'){
            sh 'npm install'
        }
        stage('build'){
            sh 'npm run build'
        }
        stage('test'){
            sh 'npm run test'
        }
    }
}
