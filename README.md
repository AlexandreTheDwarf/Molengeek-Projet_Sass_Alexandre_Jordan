# Projet récapitulatif : SCSS & Bootstrap

## Description

Ce projet est un **exercice récapitulatif** réalisé en binôme dans le cadre de notre formation. Le but principal était de mettre en pratique les compétences acquises en **SCSS** et **Bootstrap**, en recréant un site web basé sur un **template fourni**.  

Ce projet nous a permis de travailler en collaboration tout en consolidant nos connaissances.

## Objectifs pédagogiques

- Appliquer les concepts de **SCSS**, notamment :
  - Les **variables** pour centraliser les styles.
  - Les **mixins** pour éviter les répétitions.
  - Une **structure modulaire** pour une meilleure organisation des fichiers.
- Utiliser **Bootstrap** pour :
  - Structurer le site avec la **grille Bootstrap**.
  - Ajouter des **composants préconçus** (boutons, cartes, etc.).
  - Modifier et personnaliser les styles via **variables SCSS Bootstrap**.
- Travailler en **binôme** pour :
  - Gérer le projet ensemble via Git et GitHub.
  - Répartir les tâches et collaborer efficacement.

## Réflexion sur le projet

- **Ce que nous avons bien fait :**
  - Mise en place d'une structure de fichiers claire.
  - Utilisation efficace des outils SCSS (variables et mixins).

- **Difficultés rencontrées :**
  - Comprendre certains aspects de Bootstrap, notamment pour personnaliser les classes utilitaires.
  - Adapter le template à nos besoins tout en respectant la mise en page demandée.
  - Gérer certaines étapes du travail collaboratif (résolution des conflits Git, répartition des tâches).

Le projet n'est pas parfait, mais il nous a permis de mieux identifier nos forces et nos axes d'amélioration.

## Structure du projet

Voici la structure principale du projet :  

```plaintext
root/
├── index.html       # Fichier HTML principal
├── public/          # Images ou autres ressources
│   ├── scss/           # Dossier SCSS
│   │   ├── abstracts/      # Variables globales (couleurs, tailles, etc.)
│   │   ├── base/           # Reset css
│   │   ├── components/     # Boutton et navbar
│   │   ├── layouts/        # Section, footer et header
│   │   ├── theme/          # Présent mais pas utiliser dans ce projet
│   │   ├── vendors/        # Présent mais pas utiliser dans ce projet
│   │   └── style.scss       # Point d'entrée SCSS qui compile tout
│   ├── css/             # Fichiers CSS compilés
│   │   └── style.css         # Fichier CSS final
│   ├── img/          # Images ou autres ressources
│   ├── js/           # Script pour le burger menu
└── README.md        # Ce fichier
```

## Instructions pour tester le projet

1. **Cloner le projet** :  
   ```bash
   git clone <url-du-repository>
   cd <nom-du-repository>
   ```
2. **Compiler les SCSS** (si nécessaire) :  
   - Installez [Sass](https://sass-lang.com/install) si ce n'est pas encore fait.  
   - Exécutez :  
     ```bash
     sass scss/main.scss css/main.css
     ```
3. **Ouvrir le fichier HTML** dans un navigateur pour voir le rendu.

## Collaboration

### Répartition des tâches
- **[Alexandre Vandewiele]** :
  - Project Manage.
  - Mise en place de la structure SCSS.
  - Réalisation de la navbar, header, testimonial, contact et footer.
- **[Jordan Creyelman]** :
  - Réalisation de la section featured services, our services et team.

### Outils utilisés
- **Git et GitHub** pour le suivi de version.
- **Sass** pour la compilation des fichiers SCSS.

## Améliorations possibles

- Finaliser certains aspects du template qui n'ont pas pu être terminés.
- Explorer d'autres moyens de personnaliser Bootstrap.
- Améliorer la gestion des conflits lors du travail collaboratif.



