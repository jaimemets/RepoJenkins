def code

node {
  stage('Checkout') {
    checkout scm
  }

  stage('Load') {
    code = load 'example.groovy'
  }

  stage('Execute') {
    code.exampleMethod()
  }
}

code.otherExampleMethod()
