pipeline {
  agent any
  stages {
    stage('') {
      steps {
        build(propagate: true, job: 'test', quietPeriod: 15, wait: true)
      }
    }
  }
}