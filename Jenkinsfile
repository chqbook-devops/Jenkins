properties ([
    [$class: 'RebuildSettings', autoRebuild: false, rebuildDisabled: false],
    disableConcurrentBuilds(),
    parameters([string(defaultValue: '', description: 'Name of the repo which you want to create in OSM', name: 'REPO_NAME')])
])

def nodeLabel = "master"

node(nodeLabel) {
    stage("Initializing the parameters for Repo Creation")
    {
        checkout scm
    }
  stage("Reading configuration file"){
            config = readProperties file: "config.properties"
	  checkout scm
    }
}
