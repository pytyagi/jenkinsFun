pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'This pipeline runs through SCM ' 
            }
        }
        stage('Stage 2') {
            steps {
                echo 'This pipeline runs through SCM with branch master' 
            }
        }
        stage('Stage 3') {
            steps {
                echo 'This pipeline runs poll SCM' 
            }
        }
    }
}

post{
    success{
        echo 'This pipeline runs poll SCM !!!!' 
    }
}