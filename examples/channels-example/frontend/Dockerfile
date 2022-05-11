FROM nginx:1.21

COPY build /opt/sites/frontend
COPY nginx.conf /etc/nginx/nginx.conf

WORKDIR /opt/sites/frontend

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80