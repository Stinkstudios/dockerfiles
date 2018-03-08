FROM ubuntu:xenial

RUN apt-get update -y -qq && \
	apt-get install -y -qq \
    libboost-dev \
    libboost-system-dev \
    libboost-thread-dev \
    libboost-timer-dev \
    libcppnetlib-dev \
    libfdk-aac-dev \
    libjsoncpp-dev \
    libopencv-contrib-dev \
    libopencv-dev \
    libpng12-0 \
    librsvg2-dev \
    libwebp-dev \
    libzmq-dev \
    libzmq1 \
    libxml2-dev \
    libxslt1-dev \
    libtiff5-dev \
    libjpeg8-dev \
    zlib1g-dev \
    libfreetype6-dev \
    liblcms2-dev \
    libwebp-dev \
    libffi-dev \
    libssl-dev \
    libx264-dev \
    libglew-dev \
    liblz4-dev \
    libopenexr-dev \
    libucimf-dev \
    libcurl4-openssl-dev \
    libavutil-dev \
    libswscale-dev \
    libavresample-dev \
    libavformat-dev \
    libavcodec-dev \
    libthai-dev \
    librsvg2-dev

RUN apt-get install -y wget jq awscli

RUN mkdir /app
WORKDIR /app
