pipeline {
  agent any
  stages {
      stage ('Test') {
        steps {
          echo "Hallo"
          script {
            def cfg = readYaml file: './prometheus/src/config.yml'
            println cfg
          }
          sh "echo ${cfg}"
        }
      }
  }
}
