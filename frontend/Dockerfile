# Use lightweight Nginx image to serve static files
FROM nginx:alpine

# Set working directory (optional)
WORKDIR /usr/share/nginx/html

# Copy all frontend files (index.html, CSS, JS) into Nginx html folder
COPY . .

# Expose port 80 for HTTP
EXPOSE 80

# Start Nginx in foreground
CMD ["nginx", "-g", "daemon off;"]
