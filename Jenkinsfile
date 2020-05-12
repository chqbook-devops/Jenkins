node {
  stage("Reading configuration file"){
            config = readProperties file: "config.properties"
    }
  stage('scm'){
	 def list_file= "${config.files}"
	  echo "${list_file}"
	for (entry in list_file.getItems()) {
		echo "${entry}"
        }
    }
}
