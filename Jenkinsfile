pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/muhamed-ibrahim/PipelineTask.git'

      }
    }

    stage('Execute LS Command') {
      steps {
        bat '"C:\\Program Files\\Git\\bin\\bash.exe" bash_script_file.sh'
      }
    }
  }
}
