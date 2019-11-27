FROM arm32v7/postgres:12-alpine

MAINTAINER Lucas Ferreira da Silva <lferreira@inf.ufsm.br>

RUN apk add --update htop

COPY ./setup-master.sh /docker-entrypoint-initdb.d/setup-master.sh

RUN chmod 0666 /docker-entrypoint-initdb.d/setup-master.sh