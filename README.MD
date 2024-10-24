```
docker build -t my-image .

docker run -p 8080:8080 -v "${pwd}:/public" my-image

http-server 
```