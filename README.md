# chat-project

Building using maven and **tomcat7-maven-plugin**:

  ```
  mvn clean install
  mvn tomcat7:run
  ```
  
  Output:
  ```
  [INFO] Running war on http://localhost:9090/
  INFO: Starting ProtocolHandler ["http-bio-9090"]
  ```
  
  Server should listen on port 9090
  
# Testing using Simple WebSocket Client
  https://chrome.google.com/webstore/detail/simple-websocket-client/pfdhoblngboilpfeibdedpjgfnlcodoo
