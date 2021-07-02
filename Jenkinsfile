pipeline {
    agent any
    
    stages {
        stage('verify Branch') {
            steps {
                echo "${GIT_BRANCH}"
                sh script: 'docker images -a'
                sh script: '''
                cd azure-vote/
                docker images -a
                docker build -t jenkins-pipeline .
                docker images -a
                cd ..
                '''
            }
        }
    }
}