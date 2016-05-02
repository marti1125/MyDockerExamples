FROM java:8

RUN apt-get install unzip
RUN wget https://downloads.typesafe.com/play/1.4.2/play-1.4.2.zip
RUN unzip play-1.4.2.zip

ENV PATH $PATH:/play-1.4.2

# Test play
RUN play

#ENTRYPOINT ["play"]
