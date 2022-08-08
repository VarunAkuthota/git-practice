def gv

pipeline {
    agent any
    stages {
        stage("init") {
            steps {
                script {
                    echo "Init code"
                }
            }
        }
        stage("build jar") {
            steps {
                script {
                    echo "building jar"
                }
            }
        }
        stage("build image") {
            steps {
                script {
                    echo "building image"
                    //gv.buildImage()
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo "deploying"
                    //gv.deployApp()
                }
            }
        }
    }
}