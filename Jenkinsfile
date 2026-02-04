pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Récupération du code'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Build avec Maven'
                sh 'mvn clean package'
            }
        }
    }
}
