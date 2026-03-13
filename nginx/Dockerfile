# Usa a imagem oficial do Nginx
FROM nginx:alpine
# Remove a configuração padrão para evitar conflitos
RUN rm -f /etc/nginx/conf.d/default.conf
# Copia nosso arquivo de configuração personalizado
COPY nginx.conf /etc/nginx/conf.d/default.conf
