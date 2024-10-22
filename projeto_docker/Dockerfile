# Use a imagem base do NGINX
FROM nginx:1.27-alpine3.20-slim

# Define o diretório de trabalho
WORKDIR /app

# Copie o arquivo index.html para o diretório padrão do NGINX
COPY index.html /usr/share/nginx/html/index.html

# Copie a configuração personalizada do NGINX
COPY nginx.conf /etc/nginx/nginx.conf

# Exponha a porta 80
EXPOSE 80

# Comando para iniciar o NGINX
CMD ["nginx", "-g", "daemon off;"]
