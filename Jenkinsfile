pipeline {
  agent any
  stages {
    stage('step 1') {
      steps {
        sh 'echo "First Step"'
      }
    }

    stage('step 2') {
      steps {
        s3Upload 'jenkinsbucketsaurabh'
      }
    }

  }
}