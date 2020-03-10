pipeline {
    
    agent any
    //triggers { cron('H/10 * * * *') }
    
    environment {
        CURRENT_TIME = sh(script: 'date', , returnStdout: true).trim()
        OWNER = "KWON"
    }

    stages {
        
        stage("build") {
            steps {
                sh 'echo [] building the application'
                sh 'date'
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
