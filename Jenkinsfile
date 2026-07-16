pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'echo Iniciando build...'
                bat 'python --version'
                bat 'python -m py_compile hello.py'

                stash(
                    name: 'compiled-results',
                    includes: '**/*.pyc'
                )
            }
        }
    }
}