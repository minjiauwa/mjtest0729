pipeline {
  agent any
  stages {
    stage('中文') {
      steps {
        echo '中文'
        sh '''echo $t1
echo $t2
echo $t3
echo $t4
echo $t5'''
      }
    }

  }
  parameters {
    text(defaultValue: '在', description: '', name: 't1')
    choice(choices: ["啊1", "啊2"], description: '', name: 't2')
    string(defaultValue: '的的的', description: '', name: 't3', trim: false)
    booleanParam(defaultValue: true, description: '', name: 't4')
    text(defaultValue: '555', description: 'password', name: 't5')
  }
}