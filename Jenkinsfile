pipeline
 {
  agent any
  stages {
  		  stage('Build Application'){
  		  steps{
  		  bat 'mvn clean install'
  		  	}
  		  }
  		  stage('Application deploy to Cloudhub'){
  		  steps{
  		  bat 'mvn package deploy -DmuleDeploy -Denv=Sandbox'
  		  	}
  		  }
 		}
 }