#!groovy

pipeline {

stages {

        agent any

        stage('CheckOutGit'){

            steps{
                echo "Cloning the openkart project from github to container"
                checkout scm
                echo "successfully cloned the openkart project"
                sh "ls -lrth"
            }


         }


        stage('Docker Check'){
                steps{

                    script{
                        echo "chekcing docker ........................"
                        sh "docker --version"
                        sh "whoami"

                    }

                }

        }




}




}