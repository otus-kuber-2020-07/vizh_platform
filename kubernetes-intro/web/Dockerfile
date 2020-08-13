FROM node:lts-alpine

RUN adduser -u 1001 -D -h /app app app \
 && npm install --global http-server

USER app
EXPOSE 8000

CMD http-server /app -idp 8000 --robots --no-dotfiles