FROM ubuntu:16.04 

RUN apt-get update && apt-get install -y curl
COPY run.sh .
RUN chmod +x run.sh
CMD ["/run.sh"]
