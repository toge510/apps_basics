# Java

## Installation of the JDK (Java Development Kit) on Linux from Archive Files

```
wget https://download.oracle.com/java/20/latest/jdk-20_linux-x64_bin.tar.gz
tar xzfv jdk-20_linux-x64_bin.tar.gz
sudo mv jdk-20.0.2 /opt
export PATH=$PATH:/opt/jdk-20.0.2/bin/
java -version
```

* [Installation of the JDK on Linux Platforms](https://docs.oracle.com/en/java/javase/20/install/installation-jdk-linux-platforms.html#GUID-737A84E4-2EFF-4D38-8E60-3E29D1B884B8)

Compile 

```
javac MyClass.java
```
```
java MyClass
```
```
javadoc -d doc MyClass.java
```