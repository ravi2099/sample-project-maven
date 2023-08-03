pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        build(job: 'testjob', wait: true, waitForStart: true)
      }
    }

  }
}