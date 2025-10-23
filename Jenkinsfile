pipeline {
    agent any
    stages {
        stage('Clonar código') { [cite: 139]
            steps {
                // Jenkins clona el repo automáticamente con la config SCM,
                // pero el manual incluye este paso 'git' explícitamente:
                git 'https://github.com/AxelLuna04/mi-repo.git' [cite: 142]
            }
        }
        stage('Compilar') { [cite: 148]
            steps {
                sh 'echo "Compilando el proyecto..."' [cite: 152]
            }
        }
        stage('Pruebas') { [cite: 158]
            steps {
                sh 'echo "Ejecutando pruebas..."' [cite: 162]
            }
        }
    }
}