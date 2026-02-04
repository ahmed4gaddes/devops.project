pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build avec Maven'
                sh 'ls -la'
                sh 'mvn clean package'
            }
        }
    }
}
