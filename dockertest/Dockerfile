# Use a imagem oficial do PHP com Apache como base
FROM php:7.4-apache

# Define o diretório de trabalho dentro do contêiner
WORKDIR /var/www/html

# Copia os arquivos PHP da pasta local para o diretório de trabalho no contêiner
COPY . .

# Expõe a porta 80 do contêiner para acessar a aplicação web
EXPOSE 80

# Inicia o servidor Apache quando o contêiner é iniciado
CMD ["apache2-foreground"]
 