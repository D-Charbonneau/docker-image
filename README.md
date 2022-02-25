Build command:
docker build -t dallin-app:latest .

Run command:
docker run -d -P --name dallin-app dallin-app:latest

Open browser at http://localhost:port
the port is randomly chosen based on the -P tag. (Mine starts at 49153)

To find port:
run docker ps
look for:
PORTS
0.0.0.0:XXXXX->8080/tcp