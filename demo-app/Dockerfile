# Use the official Nginx base image
FROM nginx:alpine

# Remove the default Nginx configuration file
RUN rm /usr/share/nginx/html/index.html

# Copy a custom index.html file to the Nginx document root
COPY index.html /usr/share/nginx/html/

# Expose port 80 to access the web server
EXPOSE 80

# Start the Nginx server
CMD ["nginx", "-g", "daemon off;"]