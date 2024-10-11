FROM mongo:3.6.3

EXPOSE 27117

ADD run.sh /run.sh

ADD ./files/mongod.conf /etc/mongod.conf

RUN chmod +x /run.sh

CMD ["/run.sh"]
