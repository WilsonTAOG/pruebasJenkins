pipeline{
    agent any
    stages{
        stage ('Build'){
            step{
                echo "Etapa BUILD no disponible!"
            }
        }
        stage ('Test'){
            step{
                echo "Etapa TEST no diponible"
            }
        }
        stage ('Deploy'){
            steps{
                sh "docker-compose down -v"
                sh "docker-compose up -d --build"
            }
        }
    }
}
