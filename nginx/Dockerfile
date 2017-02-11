# Set nginx base image
FROM nginx

# Copy custom configuration file from the current directory
RUN mkdir -p /etc/nginx/ssl/sl
COPY nginx.key nginx.crt /etc/nginx/ssl/sl/
COPY nginx.prod.conf /etc/nginx/nginx.conf
