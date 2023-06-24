pipeline {
    agent any
    stages {
        stage('log version infor'){
            steps {
                sh 'maven version'
                sh 'maven clean install'
            }
        }
        stage('Deploy'){
            steps {
                echo "Deploying...."
    }
}
