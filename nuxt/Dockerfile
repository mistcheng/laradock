FROM node:8-alpine
LABEL MAINTAINER="mistcheng"
LABEL version="1.0"

RUN mkdir -p /app
COPY ./run.sh /run.sh
RUN chmod +x /run.sh

ENV HOST 0.0.0.0
EXPOSE 3000

WORKDIR /app

CMD ["/run.sh"]