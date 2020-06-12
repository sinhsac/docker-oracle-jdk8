Oracle Java on Docker
=====
Build a Docker image containing Oracle Java (Server JDK specifically).

The Oracle Java Server JDK provides the same features as Oracle Java JDK commonly required for Server-side Applications (i.e. Java EE application servers). For more information about Server JDK, visit the [Understanding the Server JDK](https://blogs.oracle.com/java-platform-group/understanding-the-server-jdk) blog entry from the Java Product Management team.

## Java 8
[Download Server JDK 8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) `.tar.gz` file and drop it inside folder `oracle-jdk8`. 
Build it:

```
$ cd oracle-jdk8
$ docker build -t trinhbiendich/oracle-jdk8 .
```


## Usage from docker hub
`FROM trinhbiendich/oracle-jdk8`