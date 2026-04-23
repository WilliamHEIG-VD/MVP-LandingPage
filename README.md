# Landing Page - ChefBox MVP

Une landing page moderne et responsive pour promouvoir votre application de réduction du gaspillage alimentaire.

## 📁 Fichiers

- **index.html** - Structure HTML de la landing page
- **styles.css** - Styles CSS responsifs et modernes
- **script.js** - Interactions JavaScript et animations
- **README.md** - Ce fichier

## 🚀 Démarrage Rapide

1. Ouvrez simplement `index.html` dans votre navigateur
2. La page est entièrement fonctionnelle et responsive

## 📱 Structure de la Page

### 1. **Navigation**
- Menu sticky avec logo "ChefBox"
- Liens de navigation smooth scroll

### 2. **Hero Section**
- Titre accrocheur
- Sous-titre explicatif
- Boutons d'appel à l'action (CTA)
- Mockup téléphone animé
- Statistiques clés

### 3. **Section Problème**
- Storytelling de François (étudiant)
- 4 étapes du problème en cartes
- Statistiques du gaspillage

### 4. **Section Solution**
- Processus en 3 étapes (Photo → IA → Recettes)
- Mise en avant de la simplicité

### 5. **Section Avantages**
- 6 cartes de features
- Tableau de comparaison avec les concurrents
- Points de différenciation

### 6. **Public Cible**
- 2 personas : Étudiants et Familles
- Caractéristiques et besoins de chacun

### 7. **Call-to-Action**
- Formulaire d'email pour se faire alerter
- Message de succès au soumission

### 8. **Footer**
- Liens importants
- Réseaux sociaux (à compléter)

## 🎨 Caractéristiques Visuelles

- **Couleurs**
  - Primaire : Orange (#FF6B35)
  - Secondaire : Bleu (#004E89)
  - Accent : Doré (#F7931E)

- **Typographie**
  - Police sans-serif moderne (Segoe UI)
  - Hiérarchie visuelle claire

- **Animations**
  - Transitions fluides au hover
  - Animations de scroll (fade-in)
  - Animation du téléphone (floating)
  - Compteurs animés pour les statistiques

## 📱 Responsive Design

La page est entièrement responsive sur :
- Desktop (1200px+)
- Tablette (768px - 1199px)
- Mobile (< 768px)

## ⚙️ Fonctionnalités JavaScript

- **Smooth Scroll** - Navigation fluide entre les sections
- **Intersection Observer** - Animations au scroll
- **Formulaire CTA** - Validation et message de succès
- **Modal Vidéo** - Bouton pour afficher une démo (à intégrer)

## 🔧 Personnalisation

### Modifier le nom de l'app
Cherchez "ChefBox" et remplacez par votre nom

### Modifier les couleurs
Dans `styles.css`, modifiez les variables CSS en haut :
```css
:root {
    --primary-color: #FF6B35;
    --secondary-color: #004E89;
    --accent-color: #F7931E;
}
```

### Ajouter les réseaux sociaux
Dans le footer, complétez les liens :
```html
<a href="https://facebook.com/votreapp">Facebook</a>
```

### Intégrer la vidéo
Remplacez le contenu de `.video-placeholder` par un `<iframe>` YouTube ou Vimeo

## 📈 Optimisations Futures

- [ ] Intégrer Google Analytics
- [ ] Ajouter une section de testimonials
- [ ] Intégrer une vraie vidéo de démo
- [ ] Ajouter un blog/actualités
- [ ] Intégration avec système de notification par email
- [ ] Support du mode sombre

## 💡 Conseils

1. **Pour héberger la page** : Utilisez Netlify, Vercel, ou GitHub Pages
2. **Pour les emails** : Intégrez Mailchimp, ConvertKit ou similar
3. **Pour les analytics** : Ajoutez Google Analytics ou Plausible
4. **Pour les images** : Utilisez des images de qualité pour remplacer les emojis

## 📧 Contact & Support

Pour toute question sur la landing page, n'hésitez pas à vous référer au code commenté.

---

**Version** : 1.0  
**Date** : 2024  
**Projet** : MVP HEIG-VD - Éviter le gaspillage alimentaire
