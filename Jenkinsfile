pipeline {
    agent any
    tools {
        maven 'maven'
	}
    stages {
        stage('Initialize') {
	steps {
	    echo 'Validating source code..'
	    sh 'mvn validate'
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
