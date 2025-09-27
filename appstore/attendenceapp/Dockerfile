# Use the official nginx image to serve static files
FROM nginx:stable-alpine

# Remove default nginx website
RUN rm -rf /usr/share/nginx/html/*

# Copy current directory contents into nginx html directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80
