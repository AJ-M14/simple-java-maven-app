pipeline {
    agent any

    stages {
        stage('Build') { 
            steps {
                bat 'echo %PATH% && mvn -B -DskipTests clean package' 
            }
        }
    }
}
