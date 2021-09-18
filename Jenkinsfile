pipeline {
  agent any
  stages {
      stage ('Test') {
        steps {
          echo "Hallo"
          def cfg = readYaml file: './prometheus/src/config.yml'
          echo cfg
          sh "echo ${cfg}"
        }
      }
  }
}
