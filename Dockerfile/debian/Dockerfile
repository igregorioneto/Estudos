FROM debian

LABEL app="debian"
ENV HELLO=WORLD

RUN apt-get update && apt-get install -y stress && apt-get clean

CMD stress --cpu --vm-bytes 64M --vm 1X

