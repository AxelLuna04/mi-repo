pipeline {
    agent any
    stages {
        // El stage 'Clonar código' se elimina.
        // Jenkins ya lo clonó automáticamente antes de empezar.

        stage('Compilar') {
            steps {
                sh 'echo "Compilando el proyecto..."' 
            }
        }
        stage('Pruebas') {
            steps {
                sh 'echo "Ejecutando pruebas..."' 
            }
        }
    }
}