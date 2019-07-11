pipeline {
    agent any

    stages {
	stage('Build') {
	steps {
	    withMaven(
	    maven: 'maven')
	    echo 'Building application package..'
	    sh 'mvn clean package install'
	}
    }
  }
}
