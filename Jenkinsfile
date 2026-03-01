sleep 1000
pipeline {
    agent any

    tools {
        maven 'M3'
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
