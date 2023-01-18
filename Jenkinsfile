//DECLARATIVE
pipeline {
    //agent any
    agent { docker { image 'node:13.8'} }
    stages {
        stage ("Build") {
            steps {
                sh 'node --version'
                echo "build"
            }
        }
                            
        stage ("Test") {
            steps {
                echo "Test"
            }
        }
                            
        stage ("Integrtion") {
            steps {
                echo "Test"
            }
        }
    }
}
