FROM node:20-alpine
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY manifest.json .
COPY . .
EXPOSE 3000
CMD ["node"]


