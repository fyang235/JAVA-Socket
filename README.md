# JAVA-Socket

1. create a java project using eclips.

2. create the client source file in a package and the server source file in another.

3. export jar file

4. open terminal set：
    CLASS_PATH="path/to/jar/file/client_server.jar"

5. use jar file:
    a. open a termimal and tpye:    
        java -cp server.jar com.orbbec.socket.server.GreetingServer 6066  
    b. open another terminal and type:    
        java -cp server.jar com.orbbec.socket.client.GreetingClient localhost 6066  
