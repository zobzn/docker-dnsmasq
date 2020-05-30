FROM alpine:latest

# RUN apk --no-cache add dnsmasq && echo "conf-dir=/etc/dnsmasq,*.conf" > /etc/dnsmasq.conf
RUN apk --no-cache add dnsmasq

EXPOSE 53/tcp 53/udp

# VOLUME ["/etc/dnsmasq"]
# ENTRYPOINT ["webproc","--config","/etc/dnsmasq.conf","--","dnsmasq","--no-daemon"]

CMD ["dnsmasq"]
