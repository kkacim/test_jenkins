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
                grep -o -i devops example.txt | wc -l
            }
        }
        stage('exercice2') {
            steps {
                sed 's/devops/hello_world/g' example.txt > example2.txt
                echo "After replacing devops by hello_world: "
                cat example2.txt
            }
        }
    }
}
