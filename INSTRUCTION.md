Reporsitory link: https://hub.docker.com/repository/docker/taniakolesnik/todoapp/general

To run docker, run below in Terminal:  

docker run -d -p 8080:8080 --name todo taniakolesnik/todoapp:1.0.0  

Access web site with your browser using url below:

http://localhost:8080/

To stop server run:

docker stop todo