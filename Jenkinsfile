pipeline {
  agent any
  stages {
    stage('Deploying dotnet container to Kubernetes') {
      steps {
        script {
          kubernetesDeploy(configs: "dep1.yaml", "serv1.yaml")
        }
      }
    }
  }
}
