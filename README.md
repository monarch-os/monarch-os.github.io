# Monarch OS - Site Web

Site web officiel de Monarch OS, une distribution Linux basée sur Omarchy, conçue pour les experts en cybersécurité.

## 🚀 Déploiement sur GitHub Pages

Ce site est configuré pour être déployé automatiquement sur GitHub Pages.

### Configuration automatique

1. **Fork ou clonez ce repository**
2. **Activez GitHub Pages** dans les paramètres du repository :
   - Allez dans `Settings` > `Pages`
   - Sous `Source`, sélectionnez `GitHub Actions`
3. **Poussez vos modifications** sur la branche `main` ou `master`
4. **Le déploiement se fait automatiquement** via GitHub Actions

### Structure du projet

```
.
├── .github/
│   └── workflows/
│       └── deploy.yml          # Configuration GitHub Actions
├── assets/
│   ├── logo.svg                # Logo Monarch OS
│   └── favicon.svg             # Favicon
├── index.html                  # Page d'accueil
├── 404.html                    # Page d'erreur 404
├── robots.txt                  # Configuration pour les robots
├── sitemap.xml                 # Sitemap pour le SEO
├── .nojekyll                   # Désactive Jekyll
├── .gitignore                  # Fichiers à ignorer par Git
└── README.md                   # Ce fichier
```

### Développement local

Pour tester le site localement :

1. **Clonez le repository**
   ```bash
   git clone <votre-repo-url>
   cd website
   ```

2. **Servez les fichiers statiques**
   ```bash
   # Avec Python 3
   python -m http.server 8000
   
   # Avec Node.js (si vous avez http-server installé)
   npx http-server
   
   # Avec PHP
   php -S localhost:8000
   ```

3. **Ouvrez votre navigateur** sur `http://localhost:8000`

### Technologies utilisées

- **HTML5** - Structure sémantique
- **Tailwind CSS** - Framework CSS utilitaire
- **JavaScript vanilla** - Animations et interactions
- **SVG** - Graphiques vectoriels pour le logo et favicon
- **Google Fonts** - Typographie (Inter, JetBrains Mono, Orbitron)

### Fonctionnalités

- ✅ **Design responsive** - Compatible mobile et desktop
- ✅ **Animations CSS** - Effets visuels modernes
- ✅ **Accessibilité** - Support des lecteurs d'écran
- ✅ **Performance optimisée** - Chargement rapide
- ✅ **SEO friendly** - Métadonnées optimisées
- ✅ **Page 404 personnalisée** - Gestion des erreurs

### Personnalisation

#### Couleurs

Les couleurs sont définies dans la configuration Tailwind CSS dans `index.html` :

```javascript
colors: {
    'monarch-purple': '#8B5CF6',     // Violet royal principal
    'monarch-purple-light': '#A78BFA', // Violet royal clair
    'monarch-purple-dark': '#7C3AED',  // Violet royal foncé
    'monarch-deep': '#1E1B4B',        // Arrière-plan profond
    'monarch-deeper': '#0F0B2E',      // Arrière-plan plus profond
    'monarch-card': '#312E81',        // Arrière-plan des cartes
    'monarch-text': '#E0E7FF',        // Texte clair
    'monarch-text-dim': '#C7D2FE',    // Texte atténué
    'monarch-glow': '#8B5CF6',        // Couleur de lueur principale
}
```

#### Animations

Les animations sont définies dans les keyframes CSS et peuvent être personnalisées selon vos besoins.

### Contribution

1. **Forkez le projet**
2. **Créez une branche** pour votre fonctionnalité (`git checkout -b feature/nouvelle-fonctionnalite`)
3. **Commitez vos changements** (`git commit -am 'Ajout d'une nouvelle fonctionnalité'`)
4. **Poussez vers la branche** (`git push origin feature/nouvelle-fonctionnalite`)
5. **Créez une Pull Request**

### Licence

Ce projet est sous licence open source. Voir le fichier LICENSE pour plus de détails.

### Support

Pour toute question ou problème :
- Ouvrez une [issue](https://github.com/votre-username/monarch-website/issues)
- Contactez l'équipe Monarch OS

---

**Monarch OS** - *Based on Omarchy, inspired by SkillArch*
