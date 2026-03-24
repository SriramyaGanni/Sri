FROM nginx:latest
RUN rm -rf /usr/share/nginx/html/*
COPY index.html /usr/share/nginx/html/
ExPOSE 80
CMD ["nginx", "-g", "daemon off;"]
