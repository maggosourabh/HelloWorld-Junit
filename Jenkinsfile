pipeline {
    agent any

    stages {
        stage('Initialize') {
	steps {
	    sh 'export PATH=$PATH:/opt/apache-maven-3.5.4/bin'
	    sh 'mvn --version'
	   }
	}
	stage('Build') {
	steps {
	    echo 'Building application package..'
	    sh 'mvn clean package install'
	}
    }
  }
}
