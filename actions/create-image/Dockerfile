FROM golang:1.18-bullseye

LABEL "name"="Create Image"
LABEL "version"="1.0"

COPY marketplace_image.json /
COPY entrypoint.sh /
ENTRYPOINT ["/entrypoint.sh"]
