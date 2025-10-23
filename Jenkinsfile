pipeline {
    agent any
    stages {
        stage('Clonar código') {
            steps {
                // Jenkins clona el repo automáticamente con la config SCM,
                // pero el manual incluye este paso 'git' explícitamente:
                git 'https://github.com/AxelLuna04/mi-repo.git' 
            }
        }
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