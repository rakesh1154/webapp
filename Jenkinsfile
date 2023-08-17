pipeline {
    agent {
      label 'jenkfile-node'
    }
  tools{
    maven 'maven'
    git 'git'
  }
    stages {
        stage('validate') {
            steps {
                sh 'mvn validate'
            }
        }
    }
}
