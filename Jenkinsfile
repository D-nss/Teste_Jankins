pipeline{
    agent any

    stages{
        stage ('Compilar') {
            steps {
                    echo "Iniciando processo de build..."
                    dir('C:\ProgramData\Jenkins\.jenkins\workspace\First_Pipeline\Teste_Jenkins')
                    bat 'Job1.py'
                    echo "Compilado com sucesso"
            }
        }
    }
}