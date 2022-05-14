pipeline{

agent any

stages{
        stage('SCM'){
            steps{
                echo "git pull code"
             }
         }
        stage('Deploy'){
             steps{
                  echo "deploy code" 
              }
         }
        stage('Test'){
        steps{ 
            echo "test code"
             }
          }
	stage('Deploy to prod'){
	steps{
	     echo "App deployed"
	     }
	     }
	stage('final1'){
	     {
	     echo "fina9l"
	     }
	     }
      }
 }
