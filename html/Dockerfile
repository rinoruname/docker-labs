FROM nginx:latest

# Remove the default NGINX welcome page
RUN rm -rf /usr/share/nginx/html/*

# Copy the custom HTML file into the NGINX root directory
COPY index.html /usr/share/nginx/html/
