 GNU nano 6.2                       New Buffer *                               
##For React-site
docker build -t react-js-app .
docker run -d -p 3000:80 react-js-app

## For typescript
docker build -t react-ts-app .
docker run -d -p 3001:80 react-ts-app


 ## For Static-site
FROM nginx:alpine

COPY . /usr/share/nginx/html
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
