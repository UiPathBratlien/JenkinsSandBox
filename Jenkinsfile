pipeline {
  agent any
  environment {
    EXAMPLE_KEY = credentials('868b8748-18b1-431a-b131-1756613ad7e6') // Secret value is 'sec%ret'
  }
  stages {
    stage('Example') {
      steps {
          /* CORRECT */
          bat 'echo %EXAMPLE_KEY%'
      }
    }
  }
}
