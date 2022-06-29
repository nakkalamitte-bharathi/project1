pipeline {
    agent any
    stages {
        stage('compile') {
            steps {
       		
                sh 'git clone \'https://github.com/nakkalamitte-bharathi/project1/\''
                sh '''javac project1/HelloWorld.java
		            java project1/HelloWorld'''
		}
        }
        stage('build'){
            steps{
                echo 'Enter Main Build'
            
            }
        }
        stage('archive'){
            steps{
                echo 'Enter Archive'
            }
        }
    }
}
