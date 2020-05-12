node {
  stage("Reading configuration file"){
            config = readProperties file: "config.properties"
    }
  stage('scm'){
	 def list_file= "${config.files}"
        changedFiles = []
	for (entry in changeLogSet.getItems()) {
		echo "{entry}"
        }
    }
}
