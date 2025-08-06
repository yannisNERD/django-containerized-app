
# django-containerized-app

Application de gestion d'étudiants développée avec Django, maintenant conteneurisée avec Docker pour un déploiement simplifié.
  
##  Fonctionnalités

-  **Gestion des étudiants** : Visualiser, créer et supprimer des étudiants
-  **Gestion des notes** : Créer et supprimer des notes pour chaque étudiant
-  **Génération de PDF** : Créer des bulletins de notes au format PDF avec ReportLab
-  **Interface web intuitive** : Navigation simple et ergonomique

## Prérequis

- Docker et Docker Compose installés sur votre système
- Git pour cloner le projet

## Installation

1. **Cloner le repository**
```bash
git clone https://github.com/yannisNERD/projet-AYA-DJANGO.git
cd projet-AYA-DJANGO
```

2. **Lancer l'application**
```bash
# Construire et lancer les conteneurs
docker compose up --build -d

```

3. **Accéder à l'application**
Ouvrez votre navigateur et allez sur : http://localhost:8000

## Commandes utiles

```bash
# Arrêter l'application
docker compose down

# Relancer l'application
docker compose up -d

# Voir les logs
docker compose logs web
```
