pipeline {
    agent any
    stages {
        stage ("Build"){
            steps {
                echo ("Hello Build")
                sleep(5)
                echo ("Hello Build1")
            }
        }

        stage ("Test"){
            steps {
                echo ("Hello Test")
                sleep(5)
                echo ("Hello Test1")
            }
        }

        stage ("Deploy"){
            steps {
                echo ("Hello Deploy")
                sleep(5)
                echo ("Hello Deploy1")
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
