pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        echo "building"
      }
    }
    stage("docker image build") {
      steps {
        echo "docker image building"
        sh "docker images"
      }
    }
  }
}
