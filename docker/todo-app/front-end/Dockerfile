FROM node:14.5.0-alpine
WORKDIR /app
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
ENV SKIP_PREFLIGHT_CHECK=true
RUN npm install
ENTRYPOINT [ "npm" ]
CMD [ "start" ]
