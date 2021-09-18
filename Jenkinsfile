pipeline {
  agent any
  stages {
      stage ('Test') {
        steps {
          echo "Hallo"
          script {
            def cfg = readYaml file: './prometheus/src/config.yml'
            echo cfg
          }
          sh "echo ${cfg}"
        }
      }
  }
}
