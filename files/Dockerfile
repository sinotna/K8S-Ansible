FROM haproxy:2.3
RUN mkdir /usr/share/haproxy
RUN chown haproxy:haproxy /usr/share/haproxy/
CMD ["haproxy", "-f", "/usr/local/etc/haproxy/haproxy.cfg"]
