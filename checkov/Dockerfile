FROM alpine

RUN apk add --no-cache python3 py-pip
RUN pip3 install checkov

ENTRYPOINT ["checkov"]
CMD ["--help"]