#ConsoleCommands	
	<docker build . -t <hok>/node-web-app>
	<docker images>
##Running	
	<docker run -it -p 49160:80 -m=50m --cpus="2.0" -d hok/node-web-app docker ps>
	<docker ps>
	<docker stats>
	<docker exec -it <ID> /bin/bash>
	<curl -i localhost:80>