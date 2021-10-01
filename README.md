# aapi.kt.adligo.org
This will contain a Kotlin-native app to install the AAP (Adligo Application Platform).  AAP is basically just a file structure, so that a manifest.properties file and relative paths can be used to identify parts of the JVM needed to embed the JVMs in the native processes.

* aap (root directory)
  * apps (AAP applications)
    * yourApp 
  * java
    * manifest.properties (list of JDKs, Build Tools Etc)
    * jdk-17
    * graal-11 
