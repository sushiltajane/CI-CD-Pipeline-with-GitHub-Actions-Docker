# Use the official NGINX image as base
FROM nginx:alpine

# Remove the default NGINX web files
RUN rm -rf /usr/share/nginx/html/*

# Copy your static site to NGINX html directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start NGINX in foreground
CMD ["nginx", "-g", "daemon off;"]

