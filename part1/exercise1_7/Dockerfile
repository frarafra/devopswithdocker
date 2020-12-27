FROM ubuntu:16.04 

WORKDIR /mydir 
RUN apt-get update && apt-get install -y curl 

COPY start.sh . 
RUN chmod +x ./start.sh

CMD /mydir/start.sh