FROM httpd:2.4

# Copia os arquivos da aplicação
COPY site/ /usr/local/apache2/htdocs/

# Copia configuração personalizada
COPY apache/my-app.conf /usr/local/apache2/conf/httpd.conf
