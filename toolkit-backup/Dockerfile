FROM alpine:3.23.2

RUN apk add --update python python-dev py-pip build-base postgresql-client \
    && pip install awscli==1.14.10 --upgrade --user
