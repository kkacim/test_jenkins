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
                sh """#!/bin/bash -xe
                    cd ${WORKSPACE}
                    grep -o -i devops example.txt | wc -l
                """
                
            }
        }
        stage('exercice2') {
            steps {
                echo "After replacing devops by hello_world: "
                sh """#!/bin/bash -xe
                    cd ${WORKSPACE}
                    sed 's/devops/hello_world/g' example.txt > example2.txt
                    cat example2.txt
                """   
            }
        }
    }
}
