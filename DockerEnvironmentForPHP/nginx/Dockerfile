FROM nginx:latest

# COPY ./nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf
COPY ./conf.d/default.conf /etc/nginx/conf.d/default.conf

# COPY ./app/public /var/www/html/public

#WORKDIR /app
# ADD / /app/public/
COPY ./app/public/ /var/www/html/public/
