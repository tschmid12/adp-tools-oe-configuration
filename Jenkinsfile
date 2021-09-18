pipeline {
  agent any
  stages {
      stage ('Test') {
        steps {
          echo "Hallo"
          readYaml file: './prometheus/srv/config.yml'
        }
      }
  }
}
