FROM nginx

# Copy the custom nginx configuration file
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Expose port 80 for incoming traffic
EXPOSE 80/tcp

# Start the nginx server with the custom configuration
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]