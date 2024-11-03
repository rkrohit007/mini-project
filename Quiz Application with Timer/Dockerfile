# Use an official Nginx image to serve static files
FROM nginx:alpine

# Copy the contents of the current directory to the default Nginx directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]

