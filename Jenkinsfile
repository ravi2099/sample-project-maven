pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        build(job: 'sample-project-maven', wait: true, waitForStart: true)
      }
    }

  }
}