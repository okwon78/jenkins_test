pipeline {
    
    agent any
    
    environment {
        CURRENT_TIME = "${date}"
        OWNER = "KWON"
    }

    stages {
        
        stage("build") {
            steps {
                sh 'echo [${CURRENT_TIME}] building the application'
                sh 'echo "[${CURRENT_TIME}] building the application"'
                sh 'date'
            }
        }

        stage("test") {
            steps {
                sh "echo testing the application ${OWER}"
                sh 'echo testing the application ${OWER}'
            }
        }

        stage("deploy") {
            steps {
                sh echo "deploying the application"
            }
        }


    }
}
