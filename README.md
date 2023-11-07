jradius
=======

JRadius is a Java RADIUS framework for client and server. 

# How to build

Pack the package with the parent pom.xml

# How to Run

```aidl
java -cp ".;.\lib\*" net.jradius.client.gui.JRadiusSimulator


```
# How to Debug

```aidl
java -cp ".;.\lib\*" -agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=5005 net.jradius.client.gui.JRadiusSimulator


```