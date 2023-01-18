node('linux'){

        stage('Install'){
            sh 'npm install'
        }
        stage('Build'){
            sh 'npm run build'
        }
        stage('Test'){
            sh 'npm run test'
        }

}
