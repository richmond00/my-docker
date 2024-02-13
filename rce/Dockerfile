FROM alpine

RUN apk add python3

CMD ["8.8.8.8"]

ENTRYPOINT [ "ping", "-t", "5"]

# docker image build . -t myweb:3
# docker run myweb:3
# docker run myweb:3 4.4.4.4