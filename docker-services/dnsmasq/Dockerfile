FROM alpine:latest
RUN apk --no-cache add dnsmasq
EXPOSE 53/tcp 53/udp
ENTRYPOINT ["dnsmasq", "--keep-in-foreground", "--log-queries", "--log-facility=-"]