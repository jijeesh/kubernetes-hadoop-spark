FROM jijeesh/hadoop-base:1.1.0-hadoop2.7.1-java8
MAINTAINER jijeesh

HEALTHCHECK CMD curl -f http://localhost:8042/ || exit 1

ADD run.sh /run.sh
RUN chmod a+x /run.sh

EXPOSE 8042

CMD ["/run.sh"]
