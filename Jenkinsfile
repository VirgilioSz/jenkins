pipeline {
    agent {
        label 'docker'
    }
    stages {
        stage('Saludo') {
            steps {
                sh 'echo "¡Este Pipeline se ejecuta en el agente Docker!"'
            }
        }
    }
    
    post {
        success {
                echo "Ejecucion exitosa!!!"
            }
        }
}