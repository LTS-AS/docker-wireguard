FROM debian:jessie
MAINTAINER LTS AS <havard.line@lts.no>

# Install tools
RUN set -x; \
        apt-get update \
        && apt-get install -y --no-install-recommends \
            vim
          
# Expose ports
EXPOSE 64857
