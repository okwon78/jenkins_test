pipeline {
    
    agent any
    
    envirment {
        CURRENT_TIME = ${date}
    }

    stages {
        
        stage("build") {
            steps {
                echo "building the application"
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
