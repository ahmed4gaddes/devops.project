pipeline {
    agent any
    
    tools {
        // Utilise le nom exact défini dans votre configuration Jenkins
        jdk 'JAVA_HOME' 
        maven 'M2_HOME'
    }
    
    stages {
        stage('Build') {
            steps {
                echo "Compilation du projet student-management avec Java 17"
                // On entre dans le dossier du projet avant de compiler
                dir('student-management') {
                    sh 'mvn clean package'
                }
            }
        }
    }
}
