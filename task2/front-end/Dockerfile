FROM nginx:latest
# Copy the contents of the current directory to the specified directory in the Docker image
COPY . /usr/share/nginx/html/softy-pinko-front-end

# Copy the Nginx configuration file into the Docker image
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
