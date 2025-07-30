pipeline {
  agent any

  stages {
    stage('Clone Repo') {
      steps {
        git url: 'https://github.com/your-username/your-repo.git', branch: 'main'
      }
    }

    stage('Run Ansible Playbook') {
      steps {
        ansiblePlaybook installation: 'default',
                        playbook: 'playbook.yml',
                        inventory: 'inventory.ini',
                        colorized: true
      }
    }
  }
}

