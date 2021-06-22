pipeline {
    agent any
    
    options {
    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '', daysToKeepStr: '5', numToKeepStr: '3')
    }


    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('build') {
            steps {
                echo 'building'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying'
            }
        }
        stage('test') {
            steps {
                echo 'testing'
            }
        }
    }
}
