# 🚀 Portfolio Personnel

Un portfolio moderne et élégant développé avec les dernières technologies web pour présenter mes compétences et projets de développement.

## ✨ Fonctionnalités

- **Design Moderne** : Interface utilisateur épurée et responsive
- **Performance Optimisée** : Rendu côté serveur avec Next.js 15
- **Mode Sombre/Clair** : Thème adaptatif basé sur les préférences utilisateur
- **Typographie Premium** : Utilisation des polices Geist Sans et Geist Mono
- **Animation Fluide** : Transitions et interactions soignées
- **SEO Optimisé** : Métadonnées structurées pour un référencement optimal

## 🛠️ Technologies Utilisées

### Frontend
- **[Next.js 15](https://nextjs.org/)** - Framework React avec App Router
- **[React 19](https://react.dev/)** - Bibliothèque JavaScript pour l'interface utilisateur
- **[TypeScript](https://www.typescriptlang.org/)** - Typage statique pour JavaScript
- **[Tailwind CSS 4](https://tailwindcss.com/)** - Framework CSS utilitaire

### Outils de Développement
- **[ESLint](https://eslint.org/)** - Linter pour maintenir la qualité du code
- **[Turbopack](https://turbo.build/)** - Bundler ultra-rapide pour le développement
- **[PNPM](https://pnpm.io/)** - Gestionnaire de paquets performant

### Design & UX
- **Responsive Design** - Compatible mobile, tablette et desktop
- **Thème Adaptatif** - Support automatique du mode sombre/clair
- **Polices Optimisées** - Chargement automatique avec `next/font`

## 🚀 Installation et Démarrage

### Prérequis
- Node.js 18+ 
- PNPM (recommandé) ou npm/yarn

### Installation
```bash
# Cloner le repository
git clone https://github.com/gajonedev/portfolio.git

# Naviguer dans le dossier
cd portfolio

# Installer les dépendances
pnpm install
```

### Développement
```bash
# Lancer le serveur de développement avec Turbopack
pnpm dev

# Ou avec npm
npm run dev
```

Ouvrez [http://localhost:3000](http://localhost:3000) dans votre navigateur pour voir le résultat.

### Production
```bash
# Build de production
pnpm build

# Démarrer le serveur de production
pnpm start
```

## 📁 Structure du Projet

```
portfolio/
├── app/                    # App Router de Next.js 15
│   ├── globals.css        # Styles globaux avec Tailwind
│   ├── layout.tsx         # Layout principal de l'application
│   ├── page.tsx           # Page d'accueil
│   └── favicon.ico        # Icône du site
├── public/                # Assets statiques
│   ├── *.svg             # Icônes et logos
│   └── ...
├── next.config.ts         # Configuration Next.js
├── package.json           # Dépendances et scripts
├── tailwind.config.js     # Configuration Tailwind CSS
├── tsconfig.json          # Configuration TypeScript
└── eslint.config.mjs      # Configuration ESLint
```

## 🎨 Personnalisation

### Thèmes
Le portfolio supporte automatiquement les modes clair et sombre basés sur les préférences système :

```css
/* Mode clair (par défaut) */
:root {
  --background: #ffffff;
  --foreground: #171717;
}

/* Mode sombre (auto) */
@media (prefers-color-scheme: dark) {
  :root {
    --background: #0a0a0a;
    --foreground: #ededed;
  }
}
```

### Polices
Utilisation des polices Geist optimisées par Vercel :
- **Geist Sans** : Police principale pour le texte
- **Geist Mono** : Police monospace pour le code

## 🚀 Déploiement

### Vercel (Recommandé)
Le déploiement le plus simple se fait via [Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) :

1. Connectez votre repository GitHub
2. Vercel détecte automatiquement Next.js
3. Déploiement automatique à chaque push

### Autres Plateformes
- **Netlify** : Support natif de Next.js
- **AWS Amplify** : Déploiement continu
- **Docker** : Containerisation possible

## 📱 Responsive Design

Le portfolio est entièrement responsive avec des breakpoints optimisés :
- **Mobile** : < 640px
- **Tablette** : 640px - 1024px  
- **Desktop** : > 1024px

## ⚡ Performance

- **Rendu Côté Serveur** : Temps de chargement optimisé
- **Optimisation d'Images** : Composant `next/image` automatique
- **Code Splitting** : Chargement à la demande
- **Turbopack** : Bundle ultra-rapide en développement

## 🔧 Scripts Disponibles

```bash
# Développement avec Turbopack
pnpm dev

# Build de production
pnpm build

# Serveur de production
pnpm start

# Linting du code
pnpm lint
```

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. Fork le projet
2. Créer une branche (`git checkout -b feature/nouvelle-fonctionnalite`)
3. Commit vos changements (`git commit -m 'Ajout d'une nouvelle fonctionnalité'`)
4. Push vers la branche (`git push origin feature/nouvelle-fonctionnalite`)
5. Ouvrir une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 📞 Contact

**Gajone** - Développeur Full-Stack

- 🌐 **Portfolio** : [Votre URL]
- 💼 **LinkedIn** : [Votre LinkedIn]
- 📧 **Email** : [Votre Email]
- 🐱 **GitHub** : [@gajonedev](https://github.com/gajonedev)

---

⭐ N'hésitez pas à donner une étoile au projet si vous l'appréciez !
