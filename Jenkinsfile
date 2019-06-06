pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        build(propagate: true, job: 'test', quietPeriod: 15, wait: true)
      }
    }
  }
}