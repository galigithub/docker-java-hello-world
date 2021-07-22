pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        echo "building the application"
        //sh "mvn clean install -DskipTests"
      }
    }
    stage("docker image build") {
      steps {
        echo "docker image building"
        //sh "docker login -u <username> -p <password>"
        //sh "docker images"
      }
    }
  }
}
