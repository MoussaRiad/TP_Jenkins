pipeline {
  agent any
  stages {
    stage('Slack Notification') {
      steps {
        slackSend(baseUrl: 'https://hooks.slack.com/services/', token: 'T022JGB4WTG/B033NV6MPTQ/Kcjoes62shdLcCryxL9cqVpK', channel: '#general', color: 'good', message: 'hello, Slack!', username: 'im_oukerimi')
      }
    }

    stage('Build') {
      steps {
        echo 'build'
      }
    }

  }
}