FROM mongo:3.4

MAINTAINER alberto.ontur@gmail.com

#/data/db/ sera el volumen usado para la persistencia de sesion
COPY drop/* usr/local/data/db/

#CMD es lo mismo que ENTRYPOINT pero con otro formato
CMD ["mongod", "--smallfiles", "--rest"]
