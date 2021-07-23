pipeline {
  agent { label master }
   stages {
      steps ("Env Variables"){
        sh("export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/")
        echo $JAVA_HOME
      }

   }
}
