pipeline{

agent any

stages{
        stage('SCM'){
            steps{
                 git 'https://github.com/vimallinuxworld13/simple-java-maven-app.git'
             }
         }
        stage('Deploy'){
             steps{
                  sh 'mvn clean package'
              }
         }
        stage('Test'){
        steps{ 
              sh 'java -jar target/*.jar'
             }
          }
	 stage('final1111'){
	 steps { archiveArtifacts artifacts: 'target/*.jar', followSymlinks: false
	 }
      }
 }
 }
