# Use the official Nginx image as the base image
FROM nginx:latest

# Copy a custom HTML file into the container
COPY index.html /usr/share/nginx/html/

# Expose port 80 to allow incoming traffic
EXPOSE 8080

# Command to start Nginx when the container is run
CMD ["nginx", "-g", "daemon off;"]
