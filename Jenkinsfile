pipeline {
    agent any
    stages {
        stage ('Git Checkout') {
            steps {
                echo "This Build number is : ${env.BUILD_ID}"
            }
        }
        stage ('mvn build'){
            steps{
                echo "The Build Ownaer is:  ${env.CHANGE_AUTHOR_DISPLAY_NAME}"
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
