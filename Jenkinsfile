pipeline {
  agent {'master'}
   stages {
      stage ("Env Variables"){
        steps {
          script {
            sh("export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/")
            sh ("echo JAVA_HOME")
          }
          }
      }

   }
}
