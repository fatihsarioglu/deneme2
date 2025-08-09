pipeline {
    agent { label 'webserver' }
    stages {
        stage('Run docker-compose') {
            steps {
                sh 'sudo docker compose -f /home/azureuser/devops/docker-compose.yml up -d --build --force-recreate'
            }
        }
    }
}
