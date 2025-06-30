# Usa una imagen base oficial de Nginx, que es un servidor web muy ligero y eficiente.
FROM nginx:alpine

# Copia los archivos de tu sitio web (todo el contenido de la carpeta actual) 
# al directorio donde Nginx sirve los archivos por defecto.
COPY . /usr/share/nginx/html

# Expone el puerto 80 para que Railway sepa dónde dirigir el tráfico.
EXPOSE 80 