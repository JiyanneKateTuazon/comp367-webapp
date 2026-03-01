pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/JiyanneKateTuazon/comp367-webapp.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn -v'
                sh 'mvn clean package'
            }
        }
    }
}
