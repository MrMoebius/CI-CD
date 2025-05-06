pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/MrMoebius/CI-CD.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Compilando el código...'
            }
        }
        stage('Test') {
            steps {
                echo 'Ejecutando pruebas...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Desplegando aplicación...'
            }
        }
    }
}
