node {
  stage("Reading configuration file"){
            config = readProperties file: "config.properties"
    }
  stage('scm'){
	 def list_file= "${config.files}"
	for (entry in list_file.getItems()) {
		echo "{entry}"
        }
    }
}
