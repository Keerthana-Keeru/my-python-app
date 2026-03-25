pipeline {
  agent any

  stages {
    
    stage('Clone') {
      steps {
        git url: 'https://github.com/Keerthana-Keeru/my-python-app.git',
            branch:'main'
      }
    }
    
    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
