FROM bde2020/spark-base:1.6.2-hadoop2.6

MAINTAINER Erika Pauwels <erika.pauwels@tenforce.com>

COPY master.sh /

ENV SPARK_MASTER_PORT 7077
ENV SPARK_MASTER_WEBUI_PORT 8080
ENV SPARK_MASTER_LOG /spark/logs

EXPOSE 8080 7077 6066

CMD ["/bin/bash", "/master.sh"]
