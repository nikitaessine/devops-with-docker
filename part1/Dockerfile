FROM ubuntu:20.04

RUN apt-get update && apt-get install -y curl

COPY script.sh /usr/src/app/script.sh

RUN chmod +x /usr/src/app/script.sh

CMD ["/usr/src/app/script.sh"]

