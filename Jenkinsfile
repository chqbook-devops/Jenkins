properties ([
	pipelineTriggers([pollSCM('* * * * *')])
    ])
node {
    stage('Git Checkout') {
       checkout([$class: 'GitSCM', branches: [[name: '*/master']], 
          userRemoteConfigs: [[credentialsId: 'github', url: 'https://github.com/oo4abhishek/test.git']]])
    }
}
