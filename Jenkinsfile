pipeline {
    agent any

    tools {
        maven 'M3'
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn -v'
                sh 'mvn clean package'
            }
        }
    }
}
