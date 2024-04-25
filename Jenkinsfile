pipeline {
  agent {
    dockerfile true
  }
  stages {
    stage('Build') {
      steps {
        echo 'My First Pipeline'
        sh'echo myCustomEnvVar=$myCustomEnvVar'
      }
    }

  }
}
