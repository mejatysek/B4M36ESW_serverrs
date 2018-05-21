# WordCounting server - java

Fast HTTP server counting words based on [rapidoid-http-fast](https://www.rapidoid.org/http-fast.html), streams and ConcurrentHashMap 
developed for purpose of effective software course (B4M36ESW) on [CTU](http://www.fel.cvut.cz/en/)

## Libs used
 * [rapidoid-http-fast](https://www.rapidoid.org/http-fast.html) (v5.5.4)

 ## Standard lib
  * ConcurrentHashMap
  * Streams
  ```java
   GZIPInputStream ungziped = new GZIPInputStream(new ByteArrayInputStream(data)); //GZIPInputStream is not buffered
   BufferedReader br = new BufferedReader(new InputStreamReader(new BufferedInputStream(ungziped)));
  ```
 

## Run with 
Oracle JDK 10.0.1 on [ritchie.ciirc.cvut.cz](ritchie.ciirc.cvut.cz)
```bash
java -version
# java version "10.0.1" 2018-04-17
# Java(TM) SE Runtime Environment 18.3 (build 10.0.1+10)
# Java HotSpot(TM) 64-Bit Server VM 18.3 (build 10.0.1+10, mixed mode)
```