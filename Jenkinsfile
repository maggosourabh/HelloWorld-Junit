pipeline {
    agent any

    stages {
	stage('Build') {
	withMaven(
	maven: 'maven')
	steps {
	    echo 'Building application package..'
	    sh 'mvn clean package install'
	}
    }
  }
}
