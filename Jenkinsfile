pipeline {
    agent any
    stages {
        stage ("Build"){
            steps {
                echo ("Hello Build")
            }
        }

        stage ("Test"){
            steps {
                echo ("Hello Test")
            }
        }

        stage ("Deploy"){
            steps {
                echo ("Hello Buld")
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
