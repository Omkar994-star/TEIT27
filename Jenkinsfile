pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Compile') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }
        
        stage('Run') {
             steps {
                 bat 'java HelloWorld'
             }
         }
     }
 }
