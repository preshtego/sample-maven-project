pipeline {
    agent any
    stages {
        stage('log version info'){
            steps {
                sh 'maven version'
                sh 'maven clean install'
            }
        }
    }
}
