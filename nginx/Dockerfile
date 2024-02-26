# Utiliza la imagen base de NGINX
FROM nginx:stable-alpine

# Copia el archivo de configuración personalizado al contenedor
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Expone el puerto 80 para que las solicitudes puedan llegar al contenedor
EXPOSE 80
