# Fiches Kiné

Application de révision en kinésithérapie (fiches cliniques, quiz, cartes, cas cliniques), installable sur téléphone et utilisable hors ligne.

## Contenu
- `index.html` : l'application (tout le contenu est dedans).
- `manifest.webmanifest` : nom, couleurs et icônes utilisés à l'installation.
- `sw.js` : service worker qui garde l'app en mémoire pour le mode hors ligne.
- `icons/` : icônes de l'écran d'accueil.

## Mettre en ligne (GitHub Pages)
1. Sur github.com : **New repository**, nom `fiches-kine`, **Public**, puis **Create repository**.
2. Lien **uploading an existing file** : glisse `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` et le dossier `icons`, puis **Commit changes**.
3. **Settings → Pages** : Source **Deploy from a branch**, branche `main`, dossier `/ (root)`, **Save**.
4. Une à deux minutes plus tard, l'app est en ligne à l'adresse `https://TON-PSEUDO.github.io/fiches-kine/`.

## Installer sur iPhone
1. Dans Safari, ouvre l'ancienne version (si tu en as une) → onglet 📈 **Progression** → **Exporter un fichier**.
2. Ouvre l'adresse GitHub Pages dans Safari → **Partager** → **Sur l'écran d'accueil**.
3. Dans l'app installée → 📈 **Progression** → **Importer un fichier** (l'app installée a sa propre mémoire, séparée de Safari).

## Mettre à jour
Remplace `index.html` dans le dépôt. L'app installée récupère la nouvelle version à sa prochaine ouverture avec du réseau.
