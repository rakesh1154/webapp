pipeline {
    agent {
      label 'jenkinfile-node'
    }
  tools{
    maven 'maven'
    git 'git'
  }
    stages {
        stage('package') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
