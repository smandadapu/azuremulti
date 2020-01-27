pipeline {
  agent any
  stages {
    stage('Example') {
      steps {
        bat 'echo builing from ${BRANCH_NAME}'
        bat 'echo building from env.${BRANCH_NAME}'
        bat 'echo build from env.BRANCH_NAME'
        bat 'echo build from BRANCH_NAME'
      }
    }
  }
}
