# Use the official Nginx image as the base image
FROM nginx:latest

# Copy the index.html and index.css files to the Nginx default web directory
COPY index.html /usr/share/nginx/html/index.html
COPY index.css /usr/share/nginx/html/index.css

# Expose port 80 to serve the website
EXPOSE 80

# Start the Nginx web server
CMD ["nginx", "-g", "daemon off;"]
