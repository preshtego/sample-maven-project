pipeline {
    agent any
    stages {
        stage('log version info'){
            steps {
                sh 'mvn --version'
                sh 'mvn clean install'
            }
        }
        stage('Deploy to staging'){
            steps {
                echo "Deploying...."
            }
        }
    }
}
