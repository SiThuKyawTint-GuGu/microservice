# Use the official NGINX image as a base
FROM nginx

# Remove the default NGINX configuration
RUN rm /etc/nginx/nginx.conf

# Copy your custom NGINX configuration
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80
EXPOSE 80
