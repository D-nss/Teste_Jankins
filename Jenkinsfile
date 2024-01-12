pipeline{
    agent any

    stages{
        stage ('Compilar') {
            steps {
                    echo "Iniciando processo de build..."
                    cmd_exec('cd Teste_Jenkins')
            }
        }
    }

    def cmd_exec(command) {
    return bat(returnStdout: true, script: "${command}").trim()
}
}