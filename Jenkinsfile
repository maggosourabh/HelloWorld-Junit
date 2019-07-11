pipeline {
    agent any

    stages {
        stage('Initialize') {
	steps {
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
