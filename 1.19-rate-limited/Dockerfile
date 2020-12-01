FROM nginx:1.19

COPY nginx-ssl-proxy.conf /etc/nginx/conf.d/
COPY web.key /etc/nginx/
COPY web.crt /etc/nginx/


EXPOSE 443

CMD ["nginx", "-g", "daemon off;"]
