---
# Page title
title: My page
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: banner
    content:
      title: SAGID+
      subtitle: Soutien aux métiers d’Accoroutiste à travers une Gestion Intégrale et Durable des dépendances vertes      
    design:
      columns: '1'
      background: 
        image: 
          filename: Banner.jpg
          filters:
            brightness: 0.8
          size: cover
          position: center  
          parallax: false
          text_color_light: true
  - block: collection
    id: section-1
    content:
      title: Qui sommes nous ?
      subtitle: Nous sommes plusieurs acteurs regroupés autour d’un objectif commun; créer une dynamique collective conduisant à la mise en place de pratiques d’entretien des bords de route plus durables
      text: "**Les partenaires impliqués dans le projet**"
       # Display content from the `content/post/` folder
      filters:
        folders:
          - partners
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: false
---




Pour toutes questions ou demandes vis-à-vis de la chaire, veuillez vous adresser à Brunelle Marche:
Brunelle Marche

Enseignant Chercheur - Université de Lorraine

+33.3.72.74.35.57

+33.6.70.91.05.45

brunelle.marche@univ-lorraine.fr

ENSGSI - Ecole Nationale Supérieure en Génie des Systèmes et de l’Innovation

ERPI - Equipe de Recherche sur les Processus Innovatifs

8 rue Bastien Lepage

BP 90647 - 54010 Nancy Cedex