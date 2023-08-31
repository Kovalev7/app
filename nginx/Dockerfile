FROM nginx

# Copy the Nginx config
COPY nginx.conf /etc/nginx/conf.d/nginx.conf

# Expose the port for access
EXPOSE 80/tcp

# Run the Nginx server
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
