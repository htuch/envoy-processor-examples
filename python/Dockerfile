FROM marketplace.gcr.io/google/debian11
WORKDIR /home/callouts
COPY * ./
RUN apt-get update && apt-get install -y python3-grpc-tools
EXPOSE 50051
CMD [ "/usr/bin/python3", "server.py" ]
