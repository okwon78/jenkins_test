pipeline {
    
    agent any
    
    environment {
        CURRENT_TIME = sh(script: 'date', , returnStdout: true).trim()
        OWNER = "KWON"
    }
    
    script {
        DATE_TAG = java.time.LocalDate.now()
        DATETIME_TAG = java.time.LocalDateTime.now()
    }

    stages {
        
        stage("build") {
            steps {
                sh 'echo [${DATE_TAG}][${DATETIME_TAG}] building the application'
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
