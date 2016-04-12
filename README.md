# SpringDocker

Quick and easy Spring Boot project with Docker integration.

Use this cool tweak to be able to access the container machine from Windows environment (not just the docker-host)

netsh interface portproxy add v4tov4 listenaddress=127.0.0.1 listenport=8080 connectaddress=192.168.99.100 connectport=8080

I also use the 5005 port to be able to Remote Debug

A more detailed Guide can be found here: http://test-this.ro/spring-boot-docker-integration-with-intellij-and-windows/
