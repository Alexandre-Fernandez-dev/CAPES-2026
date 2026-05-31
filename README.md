# 📚 CAPES-2026 — Préparation collective

Dépôt de préparation au CAPES 2026. Il regroupe les travaux individuels et un espace commun pour tous les camarades.

---

## 🗂️ Structure du dépôt

```
capes-2026/
├── Alexandre/      → Travaux d'Alexandre (submodule Git)
├── Roxane/         → Travaux de Roxane (submodule Git)
└── Others/         → Contributions libres de tout le monde 👇
```

---

## 👥 Pour tout le monde — Contribuer sans Git

Pas besoin de connaître Git ! Deux façons de contribuer :

### 📝 Framapad (documents collaboratifs en ligne)
Pour rédiger ensemble des notes, résumés ou plans de leçons :

> 🔗 **[Ouvrir le Framapad CAPES-2026](https://mypads2.framapad.org/mypads/index.html?/mypads/group/lecons-capes-2026-ztz6d9ti/view)**

Clique sur le lien, écris directement, c'est sauvegardé automatiquement.

### 📁 Dossier Others/ (fichiers individuels)
Pour déposer des fichiers (PDFs, documents Word, etc.) :

1. Crée un compte GitHub si tu n'en as pas : [github.com](https://github.com)
2. Demande l'accès à Alexandre pour être ajouté au dépôt
3. Ouvre le dossier [`Others/`](https://github.com/Alexandre-Fernandez-dev/CAPES-2026/tree/main/Others)
4. Clique sur **"Add file" → "Upload files"**
5. Dépose ton fichier et clique sur **"Commit changes"**

---

## 🛠️ Pour les contributeurs Git

Cloner le dépôt avec tous les submodules :

```bash
git clone --recurse-submodules git@github.com:Alexandre-Fernandez-dev/capes-2026.git
```

Mettre à jour les submodules :

```bash
git submodule update --remote
```

### Ajouter ton propre dépôt en submodule

Si tu as déjà un dépôt Git avec tes travaux, tu peux l'intégrer proprement en submodule plutôt que de passer par `Others/` :

```bash
git submodule add git@github.com:<TON_PSEUDO>/<TON_DEPOT>.git <ton_prenom>
git commit -m "feat: ajout submodule <ton_prenom>"
git push
```

> ⚠️ Ton dépôt doit être accessible (public, ou accès accordé à Alexandre). Contacte Alexandre ([@Alexandre-Fernandez-dev](https://github.com/Alexandre-Fernandez-dev)) pour qu'il intègre le submodule dans le dépôt principal.

---

## 📬 Contact

Des questions ? Contacte Alexandre ([@Alexandre-Fernandez-dev](https://github.com/Alexandre-Fernandez-dev)) directement.
