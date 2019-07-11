pipeline {
    agent any

    stages {
        stage('Build') {
	steps {
	    echo 'Building application package..'
	    sh 'mvn clean package install'
	}
    }
  }
}
