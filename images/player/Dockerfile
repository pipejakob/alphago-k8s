FROM gcr.io/beacham-gke-dev/alphago-base:0.1

RUN apt-get install -y uuid-runtime

ADD player /bin

ENTRYPOINT ["/bin/player"]
