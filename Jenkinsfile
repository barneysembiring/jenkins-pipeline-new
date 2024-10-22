pipeline {
    agent any
    stages {
        stage ("Hello"){
            steps {
                echo ("Hello World")
            }
        }
    }

    post{
        always{
            echo " I will always Hello again"
        }
        success{
            echo"Yay, success"
        }
        failure{
            echo"Oh no, failure"
        }
        cleanup{
            echo"Dont care success or error"
        }
    }
}
