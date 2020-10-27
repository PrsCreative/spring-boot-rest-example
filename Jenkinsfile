 pipeline{
	environment{
	   
	}
    agent any
    options {
        skipDefaultCheckout()
        buildDiscarder(logRotator(numToKeepStr: '5'))
    }
	stages {
        stage('Checkout & Build') {
            
        }

        stage('SonarQube analysis') {
            agent {
                docker {
                    image 'maven:3-alpine'
                    args '-v /datajkn/mvn/.m2:/root/.m2'
                }
            }
            steps {
                
            }
        }

        stage("Build & Push images") {
            
        }

        stage('Check File Before Deployment') {
            
        }

        stage('Deploy Kubernetes'){
           
        }

        stage('Check Status After Deploy'){
            
        }
        
        stage('Test Report'){
            
        }

    }// end stages
}
