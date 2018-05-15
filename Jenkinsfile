pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'mvn-build', quietPeriod: 1, wait: true, propagate: true)
      }
    }
  }
}