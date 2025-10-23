docker build -t mi-web-docker .

docker run -d -p 8080:80 mi-web-docker