FROM jenkins:2.19.4-alpine
USER root

# install plugins
COPY plugins.txt /plugins.txt
RUN /usr/local/bin/plugins.sh /plugins.txt
