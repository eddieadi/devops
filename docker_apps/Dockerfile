# Use the official NGINX image from Docker Hub
FROM nginx:latest

# Copy custom NGINX configuration (optional if you have one)
# COPY ./nginx.conf /etc/nginx/nginx.conf

# Expose port 80 in the container
EXPOSE 80

# Start NGINX when the container launches
CMD ["nginx", "-g", "daemon off;"]
