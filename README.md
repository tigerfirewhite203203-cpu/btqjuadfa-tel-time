# 🔔 Notify — Tableau de bord de notifications

Une PWA (Progressive Web App) élégante à installer sur iPhone comme app native.

---

## 🚀 Mise en ligne sur GitHub Pages

1. **Crée un repo GitHub** (ex: `notify-app`)
2. **Upload les 5 fichiers** dans le repo :
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.svg`
   - `icon-512.svg` *(même fichier que icon-192.svg, juste renommé)*
3. Va dans **Settings → Pages**
4. Source : `Deploy from a branch` → `main` → `/root`
5. Ton app sera dispo sur : `https://TON-USERNAME.github.io/notify-app/`

---

## 📱 Ajouter sur l'écran d'accueil iPhone

1. Ouvre l'URL dans **Safari** (pas Chrome !)
2. Appuie sur le bouton **Partager** ↑
3. Sélectionne **"Sur l'écran d'accueil"**
4. Nomme l'app **"Notify"** et confirme

L'app s'ouvre maintenant en plein écran, comme une vraie app.

---

## ⚙️ Utilisation

### Ajouter une source de notification
1. Appuie sur **Réglages ⚙**
2. Appuie sur **+ Ajouter une source**
3. Choisis un emoji, un nom, un message, une heure et les jours
4. Enregistre → la notification arrivera automatiquement à l'heure choisie

### Activer les notifications système
- Dans Réglages, active le toggle **🔔 Activer les notifications**
- Accepte la demande de permission
- Sur iOS 16.4+, les notifications fonctionnent même en arrière-plan

### Changer l'arrière-plan
- Réglages → section **Arrière-plan**
- Choisis parmi 6 thèmes (Nuit, Aurore, Crépuscule, Forêt, Braise, Glace)
- Ou colle l'URL d'une image

---

## 📋 Exemples de sources à créer

| Emoji | Nom | Message | Heure |
|-------|-----|---------|-------|
| 📧 | Emails | Vérifie ta boîte mail | 09:00 |
| 💪 | Sport | C'est l'heure de t'entraîner ! | 07:30 |
| 💊 | Médicaments | Pense à prendre tes vitamines | 08:00 |
| 🌙 | Bonne nuit | Pose ton téléphone, bonne nuit ! | 22:30 |
| 💧 | Hydratation | Bois un verre d'eau | 11:00 |
| 📰 | Actualités | Lis les news du jour | 12:00 |

---

## ℹ️ Notes techniques

- Toutes les données sont stockées **localement** sur ton téléphone (localStorage)
- Aucun serveur, aucune donnée envoyée ailleurs
- Fonctionne **hors ligne** après la première visite
- Compatible **iOS 16.4+** pour les notifications en arrière-plan
