## Debugging JAX-WS

```java
com.sun.xml.internal.ws.transport.http.client.HttpTransportPipe.dump = true;
```

## Debugging SSL

```java
System.setProperty("javax.net.debug", "ssl");
```

## Headless JAVA on OS X

Recent Javas default to popping up a GUI window every time the JVM
comes up, which is terrible. Fix it with:

```
export _JAVA_OPTIONS=-Djava.awt.headless=true
```

In thine shell
