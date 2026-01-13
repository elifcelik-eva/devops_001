## DevOps Projesi 001

---------------

### Docker'a terminalden login olmak için:

docker login -u KULLANICI_ADI -p  PAROLA

-------------------------------------

### CLI (Command Line Interface):

###### KonuştuğumYer emir araç : sürüm

docker pull nginx : stable-alpine3.23-perl

docker pull nginx : latest

docker pull nginx

docker push	kullaniciadi/nginx : sürümno

docker run -it -d -p 9998:80 --name mydemo2 nginx:alpine

docker login -p 123456789 -u kullaniciadi

docker ps

### Docker Image

###### Kendi projemizi Docker image haline çevimek 

Maven

###### Version 1

docker build --build-arg JAR_FILE=target/devops_001-1.0.0.jar --tag elifcelik49/devops_001:v001 .

http://localhost:9091

###### Version 2

docker build --build-arg JAR_FILE=target/devops_001-1.0.2.jar --tag elifcelik49/devops_001:v002 .

http://localhost:9092

###### Version 3

docker build --build-arg JAR_FILE=target/devops_001-1.0.3.jar --tag elifcelik49/devops_001:v003 .

http://localhost:9093
