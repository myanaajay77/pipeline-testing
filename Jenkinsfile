pipeline {
  agent { label master }
   stages {
      stage ("Env Variables"){
        steps {
            sh("export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/")
            echo $JAVA_HOME
          }
      }

   }
}
