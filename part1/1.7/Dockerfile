FROM ubuntu:20.04
WORKDIR /usr/src/app
COPY curler.sh .
RUN chmod +x curler.sh
RUN apt-get update && apt-get install -y curl
CMD ./curler.sh