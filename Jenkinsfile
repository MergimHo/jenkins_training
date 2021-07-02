@Library('https://github.com/MergimHo/shared-lib-jenkins.git') _

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