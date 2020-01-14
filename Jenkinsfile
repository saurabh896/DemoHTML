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
        s3Delete(bucket: 'jenkinsbucketsaurabh', path: 'https://jenkinsbucketsaurabh.s3-us-west-2.amazonaws.com/index.html')
      }
    }

  }
}