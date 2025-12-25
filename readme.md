docker build -t my-static-web .

docker run -d -p 8080:80 my-static-web

docker ps

Testing
http://localhost:8080
