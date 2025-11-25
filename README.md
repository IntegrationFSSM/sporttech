# Hackathon SporTech 2025-2030 Website

## 🎯 Description
Site web sophistiqué pour le Hackathon SporTech 2025-2030 organisé par la Cité de l'Innovation et la FST Marrakech.

## ✨ Fonctionnalités

### Design & Esthétique
- **Design moderne** avec glassmorphisme et dégradés
- **Animations fluides** et effets de parallaxe
- **Palette de couleurs** basée sur l'affiche officielle (bleu, rouge, blanc)
- **Typographie premium** avec Inter et Orbitron
- **Responsive** - fonctionne sur tous les appareils

### Sections
1. **Hero Section** - Présentation principale avec compte à rebours
2. **À Propos** - Contexte et objectifs du hackathon
3. **Message du Directeur** - Mot de Pr. Cherkaoui Moddafar
4. **Innovation** - Vision de l'innovation sportive
5. **Thématiques** - Les 4 axes principaux du hackathon
6. **Comité d'Organisation** - Présidence et membres du comité
7. **Calendrier** - Timeline des événements
8. **Participation** - Appel à candidature avec lien vers le formulaire
9. **Contact** - Informations de contact

### Fonctionnalités Interactives
- ⏱️ **Compte à rebours** en temps réel
- 🎨 **Animations au scroll** avec révélation progressive
- 🖱️ **Effets de survol** sophistiqués
- 📊 **Compteurs animés** pour les statistiques
- 🔄 **Effets de parallaxe** sur le fond
- 💫 **Effets de ripple** sur les boutons
- ↑ **Bouton retour en haut** automatique
- 📱 **Menu hamburger** responsive

## 📁 Structure des Fichiers

```
sporttech/
├── index.html          # Structure HTML principale
├── style.css           # Styles et design system
├── script.js           # Interactions et animations JavaScript
├── poster.jpg          # Affiche officielle
├── director.jpg        # Photo du directeur
├── president.jpg       # Photo du président
├── dean.jpg            # Photo du doyen
├── member1.jpg         # Photo membre comité 1
├── member2.jpg         # Photo membre comité 2
├── member3.jpg         # Photo membre comité 3
├── member4.jpg         # Photo membre comité 4
├── member5.jpg         # Photo membre comité 5
├── member6.jpg         # Photo membre comité 6
└── README.md          # Ce fichier
```

## 🚀 Utilisation

### Visualisation Locale
1. Ouvrez `index.html` directement dans votre navigateur
2. Ou utilisez un serveur local :
   ```bash
   # Avec Python 3
   python -m http.server 8000
   
   # Avec Node.js
   npx serve
   ```
3. Accédez à `http://localhost:8000`

### Personnalisation

#### Modifier les Photos
- Remplacez les fichiers `director.jpg`, `president.jpg`, etc. par vos propres photos
- Les images doivent être au format JPG ou PNG
- Dimensions recommandées : 800x800px minimum

#### Modifier les Noms
Dans `index.html`, recherchez et modifiez :
- Nom du président : ligne ~349
- Nom du doyen : ligne ~357
- Noms des membres du comité : lignes ~372-412

#### Modifier les Couleurs
Dans `style.css`, les variables CSS sont définies au début :
```css
:root {
    --primary-blue: #1e3a8a;
    --accent-red: #dc2626;
    /* ... */
}
```

#### Modifier la Date de l'Événement
Dans `script.js`, ligne 49 :
```javascript
const eventDate = new Date('2025-12-26T09:00:00').getTime();
```

## 🎨 Palette de Couleurs

- **Bleu Principal** : #1e3a8a
- **Bleu Clair** : #3b82f6
- **Rouge Accent** : #dc2626
- **Rouge Clair** : #ef4444
- **Blanc** : #ffffff
- **Gris** : #f3f4f6, #e5e7eb

## 📱 Responsive Design

Le site est entièrement responsive avec des breakpoints à :
- Desktop : > 1024px
- Tablet : 768px - 1024px
- Mobile : < 768px
- Small Mobile : < 480px

## ⚡ Performance

- Animations optimisées avec CSS transforms
- Lazy loading pour les images (possible)
- Throttling/debouncing pour les événements scroll
- Code JavaScript modulaire et optimisé

## 🔗 Liens Importants

- **Formulaire de candidature** : https://forms.gle/m1S76MLVDDDZMJ796
- **Email de contact** : incubation@uca.ac.ma

## 📝 Notes

- Les images des membres du comité sont des placeholders - remplacez-les par les vraies photos
- Ajoutez les vrais noms des membres du comité dans le HTML
- Le formulaire de participation redirige vers le Google Form
- Le compte à rebours s'arrête automatiquement quand l'événement commence

## 🆘 Support

Pour toute question ou problème, contactez : incubation@uca.ac.ma

---

**Université Cadi Ayyad - Cité de l'Innovation - FST Marrakech**
*La passion du sport & la puissance de la tech !*
