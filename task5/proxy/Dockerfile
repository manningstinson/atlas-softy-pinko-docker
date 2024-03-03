# Use the official Nginx image as the base image
FROM nginx:latest

# (Optional) Set working directory inside the container
WORKDIR /usr/share/nginx/html

# (Optional) Copy custom configuration files if needed
# COPY nginx.conf /etc/nginx/nginx.conf

# Copy the proxy.conf file to the specified location
COPY proxy.conf /etc/nginx/conf.d/default.conf
