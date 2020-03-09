pipeline {
    
    agent any
    
    environment {
        CURRENT_TIME = sh(script: 'date', , returnStdout: true).trim()
        OWNER = "KWON"
        STAGE_NAME = env.STAGE_NAME
    }

    stages {
        
        stage("build") {
            steps {
                sh 'echo [${CURRENT_TIME}][${OWNER}] building the application'
                sh 'echo "[${STAGE_NAME}] building the application"'
                sh 'date'
            }
        }

        stage("test") {
            steps {
                sh "echo testing the application ${OWNER}"
                sh 'echo testing the application ${OWNER}'
            }
        }

        stage("deploy") {
            steps {
                sh 'echo deploying the application'
                sh "echo deploying the application"
            }
        }


    }
}
