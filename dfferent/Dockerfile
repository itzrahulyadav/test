FROM nginx
COPY index.html /usr/share/nginx/html
RUN mkdir test
COPY index.html /test
COPY nginx.conf /etc/nginx/
CMD ["nginx", "-g", "daemon off;"]

