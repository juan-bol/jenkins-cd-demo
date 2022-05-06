pipeline {
    agent any
    stages {
        stage("Run Mario again final demo"){
            steps{
                sh "docker run -d -p 80:8080 pengbai/docker-supermario"
            }
        }
    }  
}
