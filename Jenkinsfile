pipeline
{
agent any
	stages{
	stage('clone'){
		steps{
		     git url: 'https://github.com/319Hemanth/jenkinsrepo.git'
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

