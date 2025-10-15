# Use nginx to serve static HTML
FROM nginx:alpine

# Copy HTML files to nginx default directory
COPY Devops_Intern.html /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]
