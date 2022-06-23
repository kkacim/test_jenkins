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
        stage('exercice1') {
            steps {
                echo "The number of times devops is found: "
                sh '/exercice1.sh'
                
            }
        }
        stage('exercice2') {
            steps {
                echo "After replacing devops by hello_world: "
                sh '/exercice2.sh'
            }
        }
    }
}
