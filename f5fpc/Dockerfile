from centos

RUN curl -O -k https://vpn.mtu.edu/public/download/linux_sslvpn.tgz \
    && tar xf linux_sslvpn.tgz \
    && yum -y install \
        file \
        iproute \
    && yum clean all \
    && yes "yes" | ./Install.sh

CMD f5fpc \
        --start \
        --user ${USER} \
        --password ${PASSWORD} \
        --host ${HOST} \
        --nocheck \
    || /bin/sleep infinity
