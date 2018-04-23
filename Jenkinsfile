def branch_name = env.BRANCH_NAME != null ? env.BRANCH_NAME : 'master'

pipeline {
    agent any


    stages {
      stage('provisioning tests') {
        steps {
          echo "We have run the tests against provisioning"
        }
      }
      stage('provisioning build') {
        steps {
          echo "We have built provisioning"
        }
      }
    }
}
