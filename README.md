# Mobirêve — Landing Page Preview

Prototype de landing page pour Mobirêve (Mouscron).  
Démonstration du système de relance post-visite.

## Stack
- HTML/CSS/JS statique
- Déployé sur Vercel
- Formulaire connecté à N8N webhook

## Sections
1. Hero — "Depuis 1927, le meuble de famille à Mouscron"
2. 2 showrooms avec CTA RDV
3. Marques premium
4. Avis Google
5. Formulaire visite + relance automatique
6. Footer

## Pour connecter le webhook N8N
Dans `index.html`, décommenter le bloc `fetch()` dans `submitForm()`  
et remplacer l'URL par votre endpoint N8N.
