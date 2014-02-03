## Debugging JAX-WS:

```java
com.sun.xml.internal.ws.transport.http.client.HttpTransportPipe.dump = true;
```

## Debugging SSL

```java
System.setProperty("javax.net.debug", "ssl");
```
