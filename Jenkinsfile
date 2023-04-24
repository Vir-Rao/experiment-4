pipeline {
    agent any
    stages{

        stage('REPO Cloning'){
            steps {
                bat 'xcopy /S "*" "C:/xampp/htdocs/exp-4" /Y'
            }
        }

        stage('Print done'){
            steps{
                echo 'Done!'
            }
        }
    }
}
