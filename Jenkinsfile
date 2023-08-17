pipeline {
    agent {
      label 'jenkinfile-node'
    }
  tools{
    maven 'maven'
    git 'git'
  }
    parameters {
  string defaultValue: 'dev', name: 'branch'
}
    stages {
        stage('package') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
