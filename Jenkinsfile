pipeline{
    agent any

    stages{
        stage ('Compilar') {
            def cmd_exec(command) {
    return bat(returnStdout: true, script: "${command}").trim()
}
            steps {
                    echo "Iniciando processo de build..."
                    cmd_exec('cd Teste_Jenkins')
            }
        }
    }
}