pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('exercise1') {
            steps {
                echo "The number of times devops is found: "
                sh 'exercise1.sh'
                
            }
        }
        stage('exercise2') {
            steps {
                echo "After replacing devops by hello_world: "
                sh 'exercise2.sh'
            }
        }
    }
}
