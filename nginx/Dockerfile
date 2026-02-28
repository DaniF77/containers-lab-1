FROM nginx:alpine

# Копирование конфигурации
COPY nginx.conf /etc/nginx/nginx.conf

# Копирование HTML файлов
COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]