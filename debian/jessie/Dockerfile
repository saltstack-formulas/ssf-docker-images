FROM debian:jessie

RUN apt-get update
RUN apt-get install -y curl
RUN curl -o bootstrap-salt.sh -L https://bootstrap.saltstack.com
RUN sh bootstrap-salt.sh -X
