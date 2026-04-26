<div align="center">
<img src="https://croustillant.menu/logo.png" alt="CROUStillant Logo"/>
  
# CROUStillant
CROUStillant est un projet qui a pour but de fournir les menus des restaurants universitaires en France et en Outre-Mer. 

</div>
  
# 📖 • Sommaire

- [🚀 • Présentation](#--présentation)
- [📦 • Projets](#--projets)
- [📑 • Liens](#--liens)
- [📃 • Crédits](#--crédits)

# 🚀 • Présentation

## 📜 • Description

CROUStillant est une plateforme open-source créée par des étudiants, pour des étudiants. Elle récupère automatiquement les menus des restaurants universitaires (CROUS) en France et en Outre-Mer, les stocke dans une base de données et les rend accessibles via une API, un site web, un bot Discord et une application mobile.

Ce projet était à la base dédié uniquement aux restaurants universitaires sur Reims mais a été étendu à toute la France et les Outre-Mer.

<img src="https://raw.githubusercontent.com/CROUStillant-Developpement/CROUStillantAssets/main/preview/menu.png" alt="CROUStillant Preview"/>

## 📊 • Quelques statistiques !

Les restaurants universitaires en France et en Outre-Mer c'est :
- **` 960+ `** points de restauration
- **` ~80 000 `** plats par semaine

## 📚 • Comment ça marche ?

CROUStillant récupère les menus des restaurants universitaires en France et en Outre-Mer, stocke les données puis les rend accessibles via une API, un site internet et un Bot Discord.

<img src="https://raw.githubusercontent.com/CROUStillant-Developpement/CROUStillantAssets/main/structure.png" alt="CROUStillant Structure"/>

# 📦 • Projets

## 🌐 • Services publics

| Projet | Description | Technologies |
|---|---|---|
| [CROUStillantWeb](https://github.com/CROUStillant-Developpement/CROUStillantWeb) | Site web officiel ([croustillant.menu](https://croustillant.menu)) | Next.js 16, TypeScript, Tailwind CSS |
| [CROUStillantAPI](https://github.com/CROUStillant-Developpement/CROUStillantAPI) | API publique ([api.croustillant.menu](https://api.croustillant.menu)) | Python |
| [CROUStillantBot](https://github.com/CROUStillant-Developpement/CROUStillantBot) | Bot Discord pour consulter les menus | Python, discord.py |
| [CROUStillantApp](https://github.com/CROUStillant-Developpement/CROUStillantApp) | Application mobile | React Native, Expo |

## ⚙️ • Services internes

| Projet | Description | Technologies |
|---|---|---|
| [CROUStillant](https://github.com/CROUStillant-Developpement/CROUStillant) | Tâche de fond principale : récupère et stocke les menus | Python, Docker |
| [CROUStillantData](https://github.com/CROUStillant-Developpement/CROUStillantData) | Met à jour les vues PostgreSQL et le tableau de bord Grafana | Python, Docker |
| [CROUStillantListener](https://github.com/CROUStillant-Developpement/CROUStillantListener) | Détecte l'ajout de nouveaux restaurants dans la base de données | Python, Docker |
| [CROUStillantBackup](https://github.com/CROUStillant-Developpement/CROUStillantBackup) | Sauvegarde automatique quotidienne de la base de données | Python, Docker |
| [CROUStillantDatasets](https://github.com/CROUStillant-Developpement/CROUStillantDatasets) | Publie automatiquement les datasets sur [data.gouv.fr](https://www.data.gouv.fr) | Python, Docker |

## 📚 • Librairies

| Projet | Description | Technologies |
|---|---|---|
| [CrousPy](https://github.com/CROUStillant-Developpement/CrousPy) | Librairie Python pour interagir avec l'API du CROUS | Python, aiohttp |
| [DataGouvPy](https://github.com/CROUStillant-Developpement/DataGouvPy) | Librairie Python pour interagir avec l'API de data.gouv.fr | Python, aiohttp |

## 🎨 • Ressources

| Projet | Description |
|---|---|
| [CROUStillantAssets](https://github.com/CROUStillant-Developpement/CROUStillantAssets) | Logo, images et polices du projet |

# 📑 • Liens

- [Site Web](https://croustillant.menu)
- [API](https://api.croustillant.menu)
- [Bot Discord](https://discord.com/oauth2/authorize?client_id=1024564077068025867)
- [Serveur Discord](https://discord.gg/yG6FjqbWtk)
- [GitHub](https://github.com/CROUStillant-Developpement)
- [data.gouv.fr](https://www.data.gouv.fr/fr/dataservices/api-croustillant/)

# 📃 • Crédits

Ce projet est le fruit d'une collaboration entre plusieurs étudiants de l'Université de Reims Champagne-Ardenne :

- [Paul Bayfield](https://github.com/PaulBayfield) - Fondateur du projet et développeur principal
- [Adlen Cherif](https://github.com/cherifad) - Développeur web, concepteur de l'interface utilisateur
- [Lucas Debeve](https://github.com/lucasDebeve) - Pro de la conception des bases de données, à l'origine de la base de données de CROUStillant
- [Louis Descotes](https://github.com/louisdescotes) - Développeur web, à l'origine de la page d'accueil du site de CROUStillant
- [Audric Fullhardt](https://github.com/audricfullhardt) - Créateur de l'application mobile de CROUStillant
