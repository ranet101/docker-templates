ARG mongo_version

FROM mongo:${mongo_version}

#COPY mongo.conf /usr/local/etc/mongo/mongo.conf

VOLUME /data/db /data/configdb

CMD ["mongod"]

EXPOSE 27017

