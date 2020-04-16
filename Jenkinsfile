node {
    stage('Git Checkout') {
        pipelineTriggers([pollSCM('* * * * *')])
       checkout([$class: 'GitSCM', branches: [[name: '*/master']], 
          userRemoteConfigs: [[credentialsId: 'github', url: 'https://github.com/oo4abhishek/test.git']]])
       pipelineTriggers([pollSCM('* * * * *')])
    }
}
