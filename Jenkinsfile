pipeline {
    agent any

    stages {
        stage('Clonar repositório') {
            steps {
                git url: 'https://github.com/glauccop/JenkinsDummyPipe.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo 'Executando build...'
                // comandos de build, como:
                // sh 'mvn clean install'
            }
        }

        stage('Testes') {
            steps {
                echo 'Executando testes...'
                // comandos de testes, como:
                // sh 'mvn test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Fazendo deploy...'
                // comandos de deploy, como:
                // sh './deploy.sh'
            }
        }
    }
}
