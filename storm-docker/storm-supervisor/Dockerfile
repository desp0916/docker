#FROM wurstmeister/storm:0.9.4
FROM desp0916/storm:0.10.0-beta1
MAINTAINER Wurstmeister

EXPOSE 6700
EXPOSE 6701
EXPOSE 6702
EXPOSE 6703
EXPOSE 8000

RUN /usr/bin/config-supervisord.sh supervisor
RUN /usr/bin/config-supervisord.sh logviewer
CMD /usr/bin/start-supervisor.sh




