pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build avec Maven dans le dossier student-management"
                // On entre dans le dossier contenant le pom.xml avant de lancer Maven
                dir('student-management') {
                    sh 'mvn clean package'
                }
            }
        }
    }
}
