# 🌐 Portfolio BTS SIO

**Portfolio BTS SIO** est un site web généré statiquement pour présenter le **parcours, les compétences, la veille technologique** et les **projets personnels** d’un étudiant en **BTS Services Informatiques aux Organisations (SIO)**.  
Le projet utilise **Pelican**, un générateur de site statique en Python, et un thème **Bootstrap 5** adapté aux portfolios professionnels. :contentReference[oaicite:1]{index=1}

---

## 🎯 Objectifs pédagogiques

- 📌 Structurer et présenter son **parcours académique**
- 🛠️ Mettre en valeur ses **projets techniques**
- 🧠 Documenter sa **veille technologique**
- 🌍 Créer un site statique moderne, responsive et professionnel
- 🧩 Publier le portfolio sur **GitHub Pages** ou tout autre hébergement web :contentReference[oaicite:2]{index=2}

---

## 🧱 Structure du projet
```css
portfolio-sio/
├── content/
│ ├── pages/ # Pages Markdown (parcours, compétences, contact, etc.)
│ └── veille/ # Articles de veille technologique
├── themes/
│ └── sio_portfolio/ # Thème personnalisé (Bootstrap 5 + Jinja2 templates)
├── docs/ # Version générée du site prête pour GitHub Pages
├── static/ # Fichiers statiques (CSS, JS, images)
├── pelicanconf.py # Configuration Pelican
├── publishconf.py # Configuration pour production
├── Makefile # Scripts de génération
├── README.md # Documentation (ce fichier)
└── cv_alternance.pdf # CV téléchargeable
```
---
> Ce modèle facilite la séparation entre **contenu** (Markdown) et **thème**, permettant de générer un site statique propre et réutilisable. :contentReference[oaicite:3]{index=3}

---

## 💻 Technologies Utilisées

- 🐍 **Pelican** — générateur de sites statiques en Python  
- 🧠 **Python** — scripts de génération du site  
- 🅱️ **Bootstrap 5** — framework CSS pour un design responsive  
- 📄 **Markdown** — contenus (pages, articles de veille)  
- 🌐 **Git & GitHub / GitHub Pages** — hébergement & versioning :contentReference[oaicite:4]{index=4}

---

## 🚀 Installation & Développement Local

### 1️⃣ Prérequis

- Python 3.10+  
- Git  
- (Optionnel) Virtualenv pour isoler l’environnement

---

### 2️⃣ Cloner le dépôt

```bash
git clone https://github.com/Josue4231/portfolio-sio
cd portfolio-sio
```
---

## 3️⃣ Créer un environnement Python
python -m venv venv
```
# Windows
```bash
venv\Scripts\activate
# macOS / Linux
```bash
source venv/bin/activate
```

## 4️⃣ Installer les dépendances
```bash
pip install pelican markdown
```

## 5️⃣ Lancer le serveur local
```bash
pelican -lr
```

Le site sera accessible à l’adresse suivante :

http://localhost:8000


📍 Tu peux éditer le contenu Markdown dans content/pages/ et content/veille/, puis relancer la génération. 
GitHub

---

## 📦 Générer la version finale

Pour produire la version finale du site (optimisée pour la production) :

pelican content -s publishconf.py


Les fichiers générés seront placés dans le dossier docs/, prêt à être déployé sur GitHub Pages. 

---

## 🧠 Personnalisation & Contenu
✏️ Pages principales

À propos — Présentation personnelle, formation, objectifs

Compétences — Langages, frameworks, outils maîtrisés

Projets — Liste des projets réalisés avec descriptions

Veille technologique — Articles Markdown indiquant ta veille

Contact / CV — Coordonnées & PDF téléchargeable 
GitHub

---

## 📬 Publication sur GitHub Pages

Active GitHub Pages dans les paramètres du dépôt

Choisis docs/ comme dossier source

Publie → ton portfolio sera accessible en ligne via l’URL GitHub Pages 
GitHub

---


## 👤 Auteur
Josue Kialengela‑Tazi — Étudiant en BTS SIO SLAM
Github.io: https://josue4231.github.io/portfolio-sio/
Ce portfolio a été créé pour valoriser ton parcours, compétences et projets tech.

---
