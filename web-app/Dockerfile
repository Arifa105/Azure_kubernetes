# Step 1: Use an official Nginx image as the base image
FROM nginx:alpine
 
# Step 2: Set the working directory inside the container
WORKDIR /usr/share/nginx/html
 
# Step 3: Copy the application files (HTML, CSS, JS) into the container
COPY index.html /usr/share/nginx/html/index.html
COPY style.css /usr/share/nginx/html/style.css

 
# Step 4: Expose port 80 to access the web app from the browser
EXPOSE 80
 
# Step 5: Start Nginx in the foreground (default behavior)
CMD ["nginx", "-g", "daemon off;"]