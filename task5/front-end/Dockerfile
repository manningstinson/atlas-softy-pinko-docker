# Use the latest version of nginx as base image
FROM nginx:latest

# Set working directory
WORKDIR /var/www/html/softy-pinko-front-end

# Copy softy-pinko-front-end files from submodule to the Docker image
COPY softy-pinko-front-end/ /var/www/html/softy-pinko-front-end

# Copy Nginx configuration file
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

# Expose port 9000
EXPOSE 9000
