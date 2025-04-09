FROM nginx:1.25.0
WORKDIR /app
RUN rm -rf /usr/share/nginx/html/* 
COPY static/ /usr/share/nginx/html/ 
CMD ["nginx", "-g","daemon off;"]