pipeline {
    
    agent any
    
    enviroment {
        CURRENT_TIME = ${date}
    }

    stages {
        
        stage("build") {
            steps {
                echo "[${CURRENT_TIME}] building the application"
                sh "date"
            }
        }

        stage("test") {
            steps {
                echo "testing the application"
            }
        }

        stage("deploy") {
            steps {
                echo "deploying the application"
            }
        }


    }
}
