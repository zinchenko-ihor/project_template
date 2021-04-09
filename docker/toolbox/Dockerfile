FROM alpine
RUN  apk add --update --no-cache curl jq py3-configobj py3-pip py3-setuptools python3 python3-dev
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pip bash && \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
