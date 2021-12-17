@Library("mukesh-shared-library") _
import com.hexaware.sharedlib.SharedLibrary
pipeline {
  agent any
  stages {
    stage ('Archive artifacts') {
      steps {
        new SharedLibrary(steps).startBuild()
      }
    }
  }
}
