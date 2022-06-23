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
                sh "chmod +x exercise1.sh"
                sh './exercise1.sh'
                
            }
        }
        stage('exercise2') {
            steps {
                echo "After replacing devops by hello_world: "
                sh "chmod +x exercise2.sh"
                sh './exercise2.sh'
            }
        }
    }
}
