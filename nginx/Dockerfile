# Use the official NGINX image
FROM nginx:latest

# Remove the default NGINX welcome page
RUN rm -rf /usr/share/nginx/html/*

# Copy custom NGINX configuration
COPY nginx.conf /etc/nginx/nginx.conf

# Copy the custom HTML file into the NGINX root directory
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;" ]
