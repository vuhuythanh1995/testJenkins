pipeline {
    agent any
    stages{
        stage('testJenkinsFile'){
            steps{
                git 'https://github.com/handuy/nodejs-todolist.git'
            }
        }
    }
    post {
        always{
            echo "OK"
        }
    }
}
