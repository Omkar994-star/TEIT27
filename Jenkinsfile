pipeline {
    agent any

    

    stages {

         stage('clone') {
             steps {
                 git branch: 'main', credentialsId: '9110e5bf-e36c-47c7-8c53-6cc22d4ca627', url: 'https://github.com/Omkar994-star/TEIT27.git'
             }
         }
        
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
