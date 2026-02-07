# Use official Nginx image
FROM nginx:alpine

# Copy HTML file to nginx default folder
COPY resume.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]

