@Library('jenkins-pipelines')_

pipeline {
    agent any

    stages {
        stage("Testing") {
            steps {
                sh 'ls -a'
            }
        }
    }

    post {
        always {
            cleanWs()
        }
    }
}