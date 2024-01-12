pipeline{
    agent any

    stages{
        stage ('Compilar') {
            steps {
                    echo "Iniciando processo de build..."
                    bat 'cd Teste_Jenkins'
                    bat 'Job1.py'
                    echo "Compilado com sucesso"
            }
        }
    }
}