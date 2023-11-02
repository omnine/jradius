jradius
=======

JRadius is a Java RADIUS framework for client and server. 

# How to build

Pack the package with the parent pom.xml

# How to Run

```aidl
java -cp ".;bcprov-jdk15-1.44.jar;commons-logging-1.1.jar;commons-pool-1.5.4.jar;jradius-core-1.1.5.jar;jradius-dictionary-1.1.5.jar;jradius-extended-1.1.5.jar" net.jradius.client.gui.JRadiusSimulator


```
# How to Debug

```aidl
java -cp ".;bcprov-jdk15-1.44.jar;commons-logging-1.1.jar;commons-pool-1.5.4.jar;jradius-core-1.1.5.jar;jradius-dictionary-1.1.5.jar;jradius-extended-1.1.5.jar" -agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=5005 net.jradius.client.gui.JRadiusSimulator


```