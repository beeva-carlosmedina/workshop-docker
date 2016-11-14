FROM nginx:1.11.5-alpine

MAINTAINER genDevOps

# Clean default sites
RUN rm -rf /etc/nginx/sites-enabled

# Add config
ADD config/nginx.conf /etc/nginx/nginx.conf
# Add ssl certs
ADD ssl/nginx.crt /etc/ssl/nginx.key
ADD ssl/nginx.key /etc/ssl/nginx.key
# Ports
EXPOSE 443
