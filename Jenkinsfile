pipeline {
    agent any

    stages {
        stage('Diagnóstico') {
            steps {
                bat 'whoami'
                bat 'where python'
                bat 'python --version'
                bat 'echo %PATH%'
            }
        }
    }
}