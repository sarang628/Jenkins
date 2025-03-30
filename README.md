# Jenkins

docker run -p 8082:8082 -p 24:24 -i -t --name jenkins -v /Users/sryang/jenkins:/home/jenkins ubuntu:22.04

apt get update

apt install git

apt install openjdk-21-jdk


# 실행

Download Jenkins Generic Java package (.war)

Open up a terminal in the download directory

Run java -jar jenkins.war --httpPort=8080

Browse to http://localhost:8080

Follow the instructions to complete the installation
