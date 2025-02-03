pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat '"C:\\Program Files\\Git\\bin\\bash.exe" -c "sh run_build_script.sh"'
        bat '"C:\\Program Files\\Git\\bin\\bash.exe" -c "sh run_windows_tests.sh"'
      }
    }
    stage('Test') {
      steps {
       echo "Run tests" 
      }
    }
  }
}
