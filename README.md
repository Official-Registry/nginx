# Nginx docker image  
    
## Usage  
  
`docker run -d --restart always --name mynginx -p 80:80 quay.io/lizhongwen/nginx`  
`docker run -d --restart always --name mynginx -p 80:80 -p 443:443 quay.io/lizhongwen/nginx`  
`docker run -d --restart always --name mynginx -p 80:80 -p 443:443 -v /your/app:/usr/share/nginx/html/app quay.io/lizhongwen/nginx`  
  
## Environment  
  
`echo NGINX_VERSION=${NGINX_VERSION}`  
  
## Link  
  
[https://quay.io/repository/lizhongwen/nginx]()  
[https://quay.io/repository/primeton/nginx]()  
[https://hub.docker.com/r/lizhongwen1989/nginx/]()  
