FROM nginx:latest

WORKDIR /app

COPY . /app

ENV WS_BACK_URL=http://containerMimi:5000 

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]