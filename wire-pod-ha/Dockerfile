FROM ubuntu

RUN apt-get update && apt-get install -y dos2unix avahi-daemon avahi-autoipd
# Copy data for add-on
COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]