pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('version') {
            steps {
                bat 'mvn --version'
            }
        stage('build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
