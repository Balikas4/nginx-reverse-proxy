# syntax=docker/dockerfile:1
FROM nginx:latest

# Remove default configuration
RUN rm /etc/nginx/conf.d/default.conf

# Copy your custom Nginx configuration
COPY nginx.conf /etc/nginx/nginx.conf
COPY reverse-proxy.conf /etc/nginx/conf.d/reverse-proxy.conf
