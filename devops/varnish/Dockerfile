# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Edgard Leonel <edgard@tre-mt.jus.br>" \
      org.label-schema.name="tremt-varnish" \
      org.label-schema.description="Treinamento TRE-MT Varnish image." \
      org.label-schema.vendor="Edgard Leonel"

COPY etc/varnish.vcl /etc/varnish/default.vcl
