FROM nginx:alpine

COPY nginx/default.conf /etc/nginx/conf.d/default.conf
COPY frontend/index.html /usr/share/nginx/html/
COPY frontend/about.html /usr/share/nginx/html/
COPY frontend/products.html /usr/share/nginx/html/
COPY frontend/services.html /usr/share/nginx/html/
COPY frontend/contact.html /usr/share/nginx/html/
COPY frontend/script.js /usr/share/nginx/html/

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]