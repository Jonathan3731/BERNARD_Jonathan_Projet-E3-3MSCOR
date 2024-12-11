FROM nginx:stable-alpine-slim

# Copie des fichiers HTML dans le dossier par défaut de Nginx
COPY ../html /usr/share/nginx/html

# Copie de la configuration personnalisée
COPY ./appseed-app.conf /etc/nginx/conf.d/default.conf