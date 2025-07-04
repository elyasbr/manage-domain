FROM mongo:8.0

RUN mkdir -p /etc/mongo \
 && echo "mySuperSecureReplicaKey123456" > /etc/mongo/keyfile \
 && chmod 400 /etc/mongo/keyfile \
 && chown mongodb:mongodb /etc/mongo/keyfile