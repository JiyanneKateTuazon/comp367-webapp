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
                bat 'mvn clean package'
            }
        }
    }
}
