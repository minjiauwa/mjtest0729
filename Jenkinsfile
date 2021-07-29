pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        bat(script: ''':loop
echo hello si xun huan
goto:loop''', encoding: null, label: null, returnStatus: false, returnStdout: false)
      }
    }

  }
}