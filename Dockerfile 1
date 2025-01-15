# Use a lightweight web server image
FROM nginx:alpine

# Copy the HTML file to the web server's root directory
COPY index.html /usr/share/nginx/html/

# Expose the default port used by Nginx
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
