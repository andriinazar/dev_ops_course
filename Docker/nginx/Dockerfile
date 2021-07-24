FROM nginx:latest

COPY ./public/index.html /usr/share/nginx/html/index.html

# Copy the public directory      
COPY ./public/ /app/public/

# Copy the nginx config file
COPY ./nginx/nginx.conf /etc/nginx/conf.d/default.conf
