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
                sh echo 'owner ${OWER}'
            }
        }

        stage("test") {
            steps {
                sh echo "testing the application"
            }
        }

        stage("deploy") {
            steps {
                sh echo "deploying the application"
            }
        }


    }
}
