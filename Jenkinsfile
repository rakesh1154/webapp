pipeline{
  agent {
    label 'jenkinfile-node'
  }
  tools{
    maven 'maven'
    git 'git'
  }
  stages{
    stage(validate)
      step{
        sh 'mvn validate'
      }
  }
}
