pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build'
                sh "echo ${BUILD_NUMBER}"
            }
        
        }
        stage('publish') {
            steps {
                echo 'publish'
            }
        }
        stage('sonarqube') {
            steps {
                echo 'sonarqube'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
}
