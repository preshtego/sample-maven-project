pipeline {
    agent any
    stages {
        stage('log version infor'){
            steps {
                sh 'mvn --version'
                sh 'maven clean install'
            }
        }
        stage('Deploy'){
            steps {
                echo "Deploying...."
            }
        }
    }
}
