pipeline {
  agent any

  stages {
    
    stage('clone') {
      steps {
        git url: 'https://github.com/vvce23ise0094-hue/jenkinsdemo.git',
          branch: 'main'
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
