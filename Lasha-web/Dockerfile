FROM nginx:alpine

# Copy the site exactly as-is into nginx's public folder (structure unchanged)
COPY . /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
