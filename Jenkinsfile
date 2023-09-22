@Library('samy')_

pipeline {
    agent {
        label 'worker1'
    }
    stages {
        stage('nginx-pipeline') {
            steps {
                echo 'starting pipeline'
             install()
            }
        }
    }
}
