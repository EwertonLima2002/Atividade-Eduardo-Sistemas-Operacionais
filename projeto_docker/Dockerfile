# Especifica a imagem base do Nginx
FROM nginx:1.27-alpine3.20-slim

# Define o diretório de trabalho
WORKDIR /app

# Copia a configuração do Nginx para o contêiner
COPY nginx.config /etc/nginx/nginx.conf

# Copia os arquivos HTML (você pode adicionar uma linha para cada arquivo HTML ou usar o COPY para copiar todos)
COPY index_green.html /usr/share/nginx/html/index.html
COPY index_orange.html /usr/share/nginx/html/index_orange.html
COPY index_darkgreen.html /usr/share/nginx/html/index_darkgreen.html
