FROM ubuntu:20.04
RUN apt-get update
RUN apt-get install curl -y
WORKDIR /usr/src/app
COPY ex1.8v2script.sh .
ENTRYPOINT [ "./ex1.8v2script.sh" ]
