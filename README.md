# TheManager 
## Description
TheManager Desktop est une application de gestion d'entreprise complète, conçue pour aider les propriétaires et gestionnaires de boutiques à gérer efficacement leurs activités quotidiennes. Cette application de bureau, développée avec Electron et React, offre une interface utilisateur moderne et intuitive tout en permettant une gestion hors ligne des données.

## Fonctionnalités principales
### Gestion des boutiques
- Création et gestion de plusieurs boutiques
- Configuration spécifique pour chaque boutique
- Sélection rapide entre différentes boutiques
### Gestion des clients
- Base de données complète des clients
- Enregistrement des informations personnelles (nom, prénom, email, téléphone, date de naissance)
- Recherche et filtrage des clients
### Gestion des produits
- Catalogue de produits détaillé
- Catégorisation des produits
- Association avec des marques et fournisseurs
- Gestion des prix et références
### Gestion des commandes
- Création et suivi des commandes
- Association des commandes aux clients
- Différents états de commande (en attente, validée, expédiée, etc.)
- Génération de factures au format PDF
### Gestion des employés
- Création de comptes utilisateurs pour les employés
- Attribution de rôles et permissions
- Contrôle d'accès basé sur les permissions
### Système de permissions avancé
- Création et personnalisation des profils de permissions
- Contrôle granulaire des accès aux fonctionnalités
- Permissions par catégorie (produits, clients, commandes, etc.)
### Gestion des fournisseurs
- Enregistrement des informations des fournisseurs
- Coordonnées et adresses
- Association des produits aux fournisseurs
### Gestion des marques
- Catalogue des marques disponibles
- Association des produits aux marques
### Fonctionnalités additionnelles
- Gestion des caractéristiques de produits
- Tableau de bord avec statistiques
- Mode maintenance
- Fonctionnement hors ligne avec synchronisation
## Architecture technique
### Frontend
- React avec TypeScript pour l'interface utilisateur
- React Router pour la navigation
- TanStack Query (React Query) pour la gestion des requêtes et du cache
- Framer Motion pour les animations
- Tailwind CSS avec shadcn/ui pour les composants d'interface
- Zustand pour la gestion d'état global
### Backend (Electron)
- Electron pour la création d'application de bureau multi-plateforme
- API IPC pour la communication entre le frontend et le backend
- Base de données locale pour le stockage des données
- Système de génération de PDF pour les factures
### Fonctionnalités techniques
- Gestion hors ligne des données
- Détection de l'état de la connexion réseau
- Système de mise à jour automatique
- Architecture modulaire et extensible
## Sécurité
- Système d'authentification robuste
- Gestion des rôles et permissions
- Protection des données sensibles
