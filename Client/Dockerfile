# Utiliser la dernière version de Node.js(16 est actuellement LTS, mais tu peux utiliser la dernière version stable)
FROM node:latest

# Définir le répertoire de travail dans le conteneur
WORKDIR /app

# Copier les fichiers package.json et package-lock.json
COPY package*.json /app/

# Installer les dépendances
RUN npm install

# Copier le reste du code source
COPY . /app/

# Construire l'application
RUN npm run build

# Exposer le port 3000 pour l'application React
EXPOSE 3000

# Commande pour démarrer l'application
CMD ["npm", "start"]
 
