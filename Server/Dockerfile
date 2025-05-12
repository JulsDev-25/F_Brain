# Utiliser l'image Pythoncomme base
FROM python:3.9-slim

# Définir le répertoire de travail dans le conteneur
WORKDIR /app

# Copier tout le code source dans le conteneur
COPY . .

# Exposer le port 8000 pour Django
EXPOSE 8000

# Commande pour démarrer le serveur Django
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"] 
