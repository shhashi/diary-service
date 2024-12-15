# Dockerfile
FROM docker.elastic.co/elasticsearch/elasticsearch:8.16.1

# Install the Kuromoji plugin
RUN bin/elasticsearch-plugin install analysis-icu &&  \
    bin/elasticsearch-plugin install analysis-kuromoji
