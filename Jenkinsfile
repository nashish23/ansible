pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        build(job: 'test', propagate: true, quietPeriod: 1, wait: true)
      }
    }
  }
}