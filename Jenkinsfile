pipeline {
  agent any
  stages {
      stage ('Test') {
        steps {
          cfg = readYaml(file: "./prometheus/src/config.yml")
          echo cfg
        }
      }
  }
}
