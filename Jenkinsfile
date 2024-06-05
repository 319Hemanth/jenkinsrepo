pipeline
{
agent any
	stages{
	stage('clone'){
		steps{
		     checkout scm
		     }
		      }	
	stage('compile'){
	steps{
		sh 'javac HelloWorld.java'
	     }
	}
 stage('execution'){
        steps{
                sh 'java HelloWorld'
             }
        }

     }
}

