# sample-maven-ant-integration
This maven project is used to demonstrate executing ant tasks and calling external ant build.xml from maven.
In this sample project we are trying to update an xml file element and calling an external build xml.

####To test the sample use following command: 

mvn -DEnv-Prefix=dev antrun:run 

####You can also refer to following url: 
https://maven.apache.org/plugins/maven-antrun-plugin/examples/classpaths.html
