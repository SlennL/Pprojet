pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Etapte de build'
                sh 'python3 --version'
                echo '$(hostname)'
            }
        }
        stage ('Test') {
            steps {
                echo "Etape de build"
            }
        }
        stage ('Deploy') {
            steps {
                echo "Etape de deploiement"
                sh 'echo "utilisateur en cours:" $(whoami)'
            }
        }
    }
}
