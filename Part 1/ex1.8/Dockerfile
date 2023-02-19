FROM ubuntu:20.04

RUN apt-get update

RUN apt update && apt upgrade -y

RUN apt -y install curl 

CMD echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;

# To execute the functionality
# 1) From the directory run in cmd/ terminal: docker build . -t <name>
# 2) docker run -it <name>