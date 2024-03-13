pipeline {
  agent any
  stages {
      stage ('making commit') {
          steps {
              echo "${GIT_COMMIT}"
              echo "${GIT_PREVIOUS_COMMIT}"
              echo "${GIT_BRANCH}"
              echo "${GIT_URL}"
              echo "${GIT_LOCAL_BRANCH}"
              echo "${GIT_PREVIOUS_SUCCESSFUL_COMMIT}"
          }
      }
  }
}
