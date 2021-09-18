pipeline {
  agent any
  stages {
      stage ('Test') {
        steps {
          def cfg = readYaml file: './prometheus/src/config.yml'
          echo cfg
        }
      }
  }
}
