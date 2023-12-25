pipeline {
    agent any
    stages {
        stage('Git') {
            steps {
                echo "git"
            }
            post {
                always {
                    echo "post os workingsdfbasdfn,sn"
                }
            }
        }
        stage('MVN') {
            steps {
                echo "mvn"
            }
            post {
                always {
                    echo "post os working"
                }
            }
        }
        stage('Deploy') {
            steps {
               echo "deploy"
            }
            post {
                always {
                    echo "post os working"
                }
            }
        }
    }
    post {
            always {
                    echo "post is working"
                }
            }
}
