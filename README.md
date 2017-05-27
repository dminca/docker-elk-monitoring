# Start Applications

## Java 

 - `cd java`
 - `./gradlew build`
 - `java -jar build/libs/gs-spring-boot-0.1.0.jar --server.address=127.0.0.1 --server.port=50001`
 
## Python

 - `cd python`
 - `python -m SimpleHTTPServer 50002`
 
## Javascript

 - `cd javascript`
 - `PORT=50003 node server.js`

### TODO
- pornirea aplicatiilor ca servicii (pentru simplitate toate aplicatiile vor fi pornite pe aceeasi masina)
- un load balancer care sa directioneze request-urile venite la una dintre aplicatii
- o stiva ELK pentru colectarea logurilor si monitorizarea aplicatiilor

