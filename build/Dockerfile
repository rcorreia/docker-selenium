FROM elgalu/selenium-node-base:2.44.0
MAINTAINER Selenium <selenium-developers@googlegroups.com>

COPY ./build /tmp/build
RUN chmod +x /tmp/build/install.sh \
  && chmod +x /tmp/build/**/install.sh
RUN ./tmp/build/install.sh
