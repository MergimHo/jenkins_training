@Library('https://github.com/MergimHo/shared-lib-jenkins')

pipeline {
    agent any
    
    stages {
        stage('Call Library Hello-World Function') {
            steps {
                script {
                    helloWorld()
                }
            }
        }
    }
}