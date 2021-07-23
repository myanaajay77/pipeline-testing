pipeline {
  agent { node master }
   stages {
      stage ("Env Variables"){
        steps {
          script {
            sh("export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/")
            echo $JAVA_HOME
          }
          }
      }

   }
}
