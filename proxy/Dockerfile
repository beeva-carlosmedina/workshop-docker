FROM nginx:1.11.5-alpine

MAINTAINER genDevOps

# Clean default sites
RUN rm -rf /etc/nginx/sites-enabled

# Add config
ADD config/nginx.conf /etc/nginx/nginx.conf

# Add ssl
ADD ssl/nginx.crt /etc/nginx/ssl/nginx.crt
ADD ssl/nginx.key /etc/nginx/ssl/nginx.key

# Ports
EXPOSE 443
