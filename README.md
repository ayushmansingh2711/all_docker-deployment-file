## For React 
docker build -t react-js-app .
docker run -d -p 3000:80 react-js-app

## For typescript 

docker build -t react-ts-app .
docker run -d -p 3001:80 react-ts-app



 ## for static site 

 docker build -t static-site .
docker run -d -p 8080:80 static-site
