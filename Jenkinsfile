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
        echo argUrl
      }
    }
  }
}
