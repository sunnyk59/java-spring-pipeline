pipeline {
  agent any 

  stages {
    stage('Checkout') {
      steps {
        sh 'echo passed'
        //git branch: 'test', url: 'https://github.com/iam-veeramalla/Jenkins-Zero-To-Hero.git'
      }
    }
    stage('Build with Maven') {
      steps {
        sh 'echo Build and Test'
        sh 'mvn -version'
        //sh 'ls -ltr'
        // build the project and create a JAR file
        //sh 'cd java-maven-sonar-argocd-helm-k8s/spring-boot-app && mvn clean package'
      }
    }   
  }
}
