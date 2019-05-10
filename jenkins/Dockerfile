FROM jenkins/jenkins:lts

USER root

RUN \
    apt-get update && \
    DEBIAN_FRONTEND=noninteractive \
    apt-get install --quiet --yes --fix-missing \
    python-pip \
    ruby-full \
    jq

