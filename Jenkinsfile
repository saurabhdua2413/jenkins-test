pipeline {
  agent any
  stages {
    stage('ansible-deployment') {
      steps {
        ansiblePlaybook(playbook: 'playbook.yml', colorized: true, inventory: '/home/saurabh/Windows_Demo/hosts')
      }
    }
  }
}