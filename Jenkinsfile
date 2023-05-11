node(){
   stage("clone repo"){
      deleteDir()
      git branch: "master" , url: 'https://github.com/Aparna-devi-chinnu-R/yamlFileLocation.git'
      def files = new File("yamlFileLocation/")
      files.eachFileRecurse (FileType.FILES) { file ->
              fileList << file
            }
   }
}