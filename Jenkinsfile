pipeline {
    agent any
    options {
        disableResume()
    }
    stages {
        stage('scm') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/AVINASH34/jenkins.git'
            }
        }
        stage('sample stage') {
            steps {
                echo 'Hello How Are You?'
                sh sleep 10s
            }
        }
        stage( 'na' ){
            steps {
                echo 'Avinash'
            }
        }
    }
}
