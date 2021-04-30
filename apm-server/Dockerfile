ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/apm/apm-server:${ELK_VERSION}

ADD config/apm-server.yml /usr/share/apm-server/apm-server.yml
#RUN chmod go-w /usr/share/apm-server/apm-server.yml

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
