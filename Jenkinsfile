pipeline {
    agent any
    stages {
        stage ('Git Checkout') {
            steps {
                bat "dir"
                CurrentBuild.result
            }
        }
        stage ('mvn build'){
            steps{
                bat "dir"
            }
        }
        stage ('test'){
            steps{
                bat "dir"
                
            }
        }
        stage ('deploy'){
            steps{
                bat "dir"
                
            }
        }
        stage('Quality Analysis') {
            parallel {
                stage ('Integration Test'){
                    steps {
                        bat "dir"
                    }
                }
                stage ('Test'){
                    steps {
                        bat "dir"
                    }
                }
            }
        }
    }
}
