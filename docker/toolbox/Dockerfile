FROM alpine
RUN apk add --no-cache wget python py-pip
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
