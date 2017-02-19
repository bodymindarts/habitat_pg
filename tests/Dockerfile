FROM alpine:3.4

# psql
RUN set -x \
  && apk add --update bash jq curl postgresql py-pip python-dev alpine-sdk linux-headers \
   && rm -rf /var/cache/apk/*
# RUN pip install wal-e==0.9.2 awscli envdir --upgrade

COPY ./tasks/  /tasks

CMD ["/bin/true"]
