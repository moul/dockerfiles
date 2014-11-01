FROM ubuntu:latest
MAINTAINER Manfred Touron <m@42.am>
RUN apt-get update
RUN apt-get -yq install mkvtoolnix && apt-get clean
CMD ["echo", "mkvinfo|mkvinfo-text|mkvmerge|mkvpropedit|mkvextract"]
