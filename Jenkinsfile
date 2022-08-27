pipeline {
    agent { docker {Image 'maven:3.3.3' } }
    stages {
        stage('log version info'){
            steps {
                sh 'maven version'
                sh 'maven clean install'
            }
        }
    }
}
