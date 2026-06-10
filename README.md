Bonjour,

Le projet d'interface d'évaluation est terminé et prêt à être intégré avec votre backend.

## Fichier : index.html

### Pour une utilisation immédiate (test/démo) :
- Ouvrir directement dans le navigateur
- Utilise LocalStorage pour stocker les données
- Aucune installation requise

### Pour connecter à votre API :
1. Remplacer les fonctions de stockage LocalStorage par des appels fetch()
2. Configurer l'URL de votre API dans une variable globale
3. Les données sont au format JSON (voir console)

### Endpoints API nécessaires :
- GET /api/evaluations → Récupérer toutes les évaluations
- POST /api/evaluations → Sauvegarder une évaluation
- GET /api/jurors → Récupérer la liste des jurés
- POST /api/jurors → Ajouter un juré
- DELETE /api/jurors/:id → Supprimer un juré

Toute la logique de calcul des moyennes (individuelle et générale) 
est déjà implémentée côté front-end.

Dépôt Git : https://github.com/Jihadhaliba/Syst-me-d-valuation---Jurys
