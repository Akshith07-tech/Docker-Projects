# Use lightweight nginx image
FROM nginx:alpine

# Copy static files into nginx default directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]
