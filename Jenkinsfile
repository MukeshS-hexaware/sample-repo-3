pipeline {
  agent any
  stages {
    stage ("Hello") {
      steps {
        echo "Hello, World"
      }
    }
    stage ("Echo parameters") {
      steps {
        echo env.argUrl
        echo "This is to check if the child pipeline created by DSL gets auto-triggered"
      }
    }
  }
}
