# DJ Playlist AI 🎧

Générateur de playlists IA pour DJs événementiels (mariages, anniversaires, soirées privées).

## Fichiers du projet

```
djplaylistai/
├── index.html     → Landing page (page d'accueil publique)
├── app.html       → Application principale
├── vercel.json    → Configuration Vercel
└── README.md      → Ce fichier
```

## Déploiement sur Vercel (5 minutes)

### Étape 1 — Créer un compte Vercel
1. Va sur https://vercel.com
2. Clique "Sign Up" → connecte-toi avec GitHub ou email

### Étape 2 — Déployer les fichiers
1. Sur le dashboard Vercel, clique **"Add New Project"**
2. Choisis **"Deploy from your computer"** ou glisse-dépose le dossier
3. Vercel détecte automatiquement le vercel.json
4. Clique **Deploy**

### Étape 3 — Ton site est en ligne !
- URL automatique : `djplaylistai.vercel.app`
- Landing page : `/`
- Application : `/app`

### Étape 4 — Domaine personnalisé (optionnel)
1. Achète `djplaylistai.fr` sur OVH (~10€/an)
2. Dans Vercel → Settings → Domains → ajoute ton domaine
3. Suis les instructions DNS de Vercel

---

## Configuration Spotify

1. Va sur https://developer.spotify.com/dashboard
2. Crée une app "DJ Playlist AI"
3. Redirect URI : `https://TON-DOMAINE.vercel.app/app.html`
   ⚠️ Met à jour le Redirect URI avec ta vraie URL après déploiement !
4. Copie le Client ID et colle-le dans l'app

---

## Technologies utilisées

- **HTML / CSS / JavaScript** — Zéro dépendance, zéro framework
- **API Anthropic Claude** — Génération IA des playlists
- **API Spotify** — Envoi des playlists vers Spotify
- **Vercel Storage** — Sauvegarde persistante des playlists

---

## Mises à jour

Pour mettre à jour l'app après déploiement :
1. Modifie le(s) fichier(s) concerné(s)
2. Re-dépose les fichiers sur Vercel (ou push sur GitHub si connecté)
3. Vercel redéploie automatiquement en ~30 secondes

---

## Prochaines étapes suggérées

- [ ] Connecter Stripe pour les paiements (plan Pro DJ à 19€/mois)
- [ ] Ajouter un export PDF imprimable
- [ ] Créer un système de comptes utilisateurs
- [ ] Ajouter d'autres langues (anglais, espagnol)

---

Fait avec ❤️ pour les DJs événementiels · 2026
