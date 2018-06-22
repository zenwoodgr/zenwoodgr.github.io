pipeline {
  agent any
  stages {
    stage('Check html') {
      steps {
        echo 'Look here'
        git(url: 'https://github.com/zenwoodgr/zenwoodgr.github.io', branch: 'master', changelog: true)
        writeFile(file: 'index.html', text: 'Sample html')
      }
    }
  }
}