//DECLARATIVE
pipeline {
    //agent any
    agent { docker { image 'maven:3.6.3'} }
    stages {
        stage ("Build") {
            steps {
                sh 'mvn --version'
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
