pipeline {
    agent any
    
    stages {
        stage('verify Branch') {
            steps {
                echo "${GIT_BRANCH}"
                sh script: "sudo chmod 666 /var/run/docker.sock"
                sh script: 'docker images -a'
            }
        }
    }
}