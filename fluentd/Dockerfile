ARG FLUENTD_VERSION
FROM fluent/fluentd:$FLUENTD_VERSION
USER root

# https://docs.fluentd.org/output/elasticsearch
RUN gem install fluent-plugin-elasticsearch --no-document


USER fluent