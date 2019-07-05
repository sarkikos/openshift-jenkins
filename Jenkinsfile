node {
  stage('Print environment variables') {
    echo sh(returnStdout: true, script: 'env')
  }

  stage('Build and tag Docker image') {
    sh "docker build ."
  }
}