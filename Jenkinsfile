stages {
  agent { node { label 'jenkins-s1.lvn.broadcom.net' } }
  stage('Build') {
    steps {
      sh 'echo "This is my first step"'
    }
  }
  stage('Test') {
    steps
      sh 'echo "This is my Test step"'
    }
  }
  stage('Deploy') {
    steps {
      sh 'echo "This is my Deploy step"'
    }
  }
}
