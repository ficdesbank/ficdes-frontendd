# FICDES BANK S.A — Frontend Vitrine (Dépôt Public)

Site vitrine institutionnel de FICDES INVESTMENT GROUP.

## ⚠️ Sécurité

Ce dépôt est **intentionnellement public** et ne contient que :
- La page d'accueil vitrine (`index.html`)
- Les styles globaux (`styles.css`)
- Les assets vitrines (`assets/`)

**Il ne contient PAS :**
- Les pages CPF (formulaires d'inscription, paiement, carte)
- La logique d'API (`ficdes-shared.js`)
- Les tokens, clés ou secrets

Les pages CPF sont hébergées sur `https://app.ficdesbank.net` depuis un **dépôt privé séparé**.

## Structure

```
ficdes-frontend-PUBLIC/
├── index.html        ← Page vitrine (publique, indexable Google)
├── styles.css        ← Styles vitrine
├── assets/
│   ├── logo.png
│   ├── hero-bg.jpg
│   └── ...
└── .gitignore
```

## Déploiement

Déployer sur Netlify, Vercel, ou GitHub Pages :
```bash
# Netlify CLI
netlify deploy --prod --dir .

# Ou simplement connecter ce dépôt GitHub à Netlify/Vercel
```

Le domaine principal `ficdesbank.net` pointe vers ce dépôt.
Le sous-domaine `app.ficdesbank.net` pointe vers le dépôt privé.

## Contact
webmaster@ficdesbank.net — © 2025 FICDES INVESTMENT GROUP
