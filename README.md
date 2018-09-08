# A static landing page inside a docker container

Steps to run this demo:
* docker build -t webserver-image:v1 .
* docker run -d -p 80:80 webserver-image:v1
