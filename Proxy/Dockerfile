# Utiliser l'image officielle NGINX
FROM nginx:latest

# Copier le fichier de configuration personnalisé de NGINX dans le conteneur
COPY ./nginx/default.conf /etc/nginx/conf.d/default.conf

# Copier le reste des fichiers nécessaires (si tu as des fichiers spécifiques à NGINX, sinon tu peux ignorer cette ligne)
#COPY ./html /usr/share/nginx/html


# Exposer le port 80
EXPOSE 80

