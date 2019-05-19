pipeline {
  agent any
  stages {
    stage('initial') {
      agent any
      steps {
        git(url: 'https://github.com/maishsk/test-pipeline.git', poll: true)
      }
    }
  }
}
