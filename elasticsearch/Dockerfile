FROM elasticsearch:7.10.1
LABEL maintainer="GAITERJONES"
# Magento 2 required plugins
# https://github.com/elastic/elasticsearch-analysis-icu
# https://github.com/elastic/elasticsearch-analysis-phonetic
RUN \
    elasticsearch-plugin install analysis-icu && \
    elasticsearch-plugin install analysis-phonetic
