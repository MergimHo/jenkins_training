pipeline {
    agent any
    
    stages {
        stage('verify Branch') {
            steps {
                echo "${GIT_BRANCH}"
                sh script: 'docker images -a'
            }
        }
    }
}