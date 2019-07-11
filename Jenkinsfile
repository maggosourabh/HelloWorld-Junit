pipeline {
    agent any
    tools {
        maven 'maven'
	}
    stages {
	stage('Build') {
	steps {
	    echo 'Building application package..'
	    sh 'mvn clean package install'
	}
    }
  }
}
