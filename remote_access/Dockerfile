ARG BUILD_FROM
FROM $BUILD_FROM

# Setup base
RUN apk add --no-cache nginx openssl openssh-client coreutils bind-tools curl sed socat tzdata oath-toolkit-oathtool tar libidn jq

# Copy data
COPY data/run.sh /
COPY data/nginx.conf /etc/

COPY rootfs /
RUN ln -s /root/.acme.sh/acme.sh /usr/local/bin/acme.sh

RUN chmod a+x /usr/local/bin/acme.sh
RUN chmod a+x ./run.sh

CMD [ "/run.sh" ]
