FROM node:12-alpine

ENV DATABASE_HOST="change me"
ENV DATABASE_PORT="change me"
ENV DATABASE_NAME="change me"
ENV DATABASE_USERNAME="change me"
ENV DATABASE_PASSWORD="change me"

LABEL org.opencontainers.image.title="image" \
      org.opencontainers.image.title="image" \
      org.opencontainers.image.title="image" \    
      org.opencontainers.image.title="image" 
 

COPY . app
WORKDIR app
RUN npm install

EXPOSE 3000
CMD npm start



