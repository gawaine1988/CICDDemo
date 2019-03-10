pipeline {
    agent any
    tools {
            maven 'maven'
            jdk   'jdk1.8'
        }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}