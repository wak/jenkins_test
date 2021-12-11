pipeline {
  agent any
  parameters {
    choice(name: 'PLATFORM_FILTER', choices: ['all', 'linux', 'windows', 'mac'], description: 'Run on specific platform')
  }
  stages {
    stage('step1') {
      steps {
        echo 'hello'
        sh 'echo world'
      }
    }

  }
  environment {
    MyENV = 'Default'
  }
}