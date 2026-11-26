# Oumar Ba Consulting — Site + Formation HCD

Site bilingue (FR/EN) du cabinet **Oumar Ba Consulting**, positionné comme une
agence de conseil en Human-Centered Design (HCD) et Service Design fondée et
dirigée par Oumar Ba, avec la page d'inscription à sa formation HCD.

## 📁 Structure

- `index.html` — Site principal : Profil, **Services**, Expérience, **Études de cas**, Compétences, Formation, Contact, CV téléchargeable
- `formation-hcd.html` — Page d'inscription à la formation HCD (13 juillet 2026, Dakar)
- `Oumar_Ba_CV_2025.pdf` — CV à jour (3 pages)
- `vercel.json` — Configuration de routage Vercel

## ✨ Ce qui a changé dans cette version

- **Rebranding** : nom du site changé en "Oumar Ba Consulting", positionnement agence de conseil (et non plus portfolio personnel) dans le hero, le titre de page, le footer et les traductions FR/EN
- **Section "Nos Services"** ajoutée juste après le hero (6 offres : Recherche HCD, Service Design, SBC Research, Formation, Prototypage, Coaching Innovation)
- **Études de cas mises en avant** : 3 missions vedettes (One Acre Fund, Dalberg/GAVI, AccèsBanque Madagascar) présentées en grand format avec structure Défi / Approche / Résultat + badges d'impact chiffrés ; les 12 autres missions restent dans la grille "Autres missions"
- **Animations** : barre de progression de scroll, apparitions au défilement (fade-in + translate) sur les cartes, formes animées en fond du hero, compteurs de statistiques (8+ / 10+ / 15+) qui s'incrémentent à l'ouverture
- Navigation mise à jour avec un lien "Services" et "Études de cas" (au lieu de "Projets")

Le site met en avant la formation via :
- un bouton **"Formation HCD"** dans la barre de navigation
- un bouton sous les CTA du bloc d'accueil

La page formation (`formation-hcd.html`) renvoie vers le site principal via son
bouton "Découvrir Oumar Ba Consulting".

## 🚀 Déploiement sur GitHub + Vercel

### 1. Créer le repo GitHub

```bash
cd oumar-ba-site
git init
git add .
git commit -m "Portfolio + formation HCD"
git branch -M main
git remote add origin https://github.com/<votre-utilisateur>/oumar-ba-site.git
git push -u origin main
```

### 2. Connecter le repo à Vercel

1. Allez sur [vercel.com/new](https://vercel.com/new)
2. Importez le repo GitHub que vous venez de créer
3. Framework Preset : **Other** (site statique, `vercel.json` gère déjà tout)
4. Cliquez **Deploy**
5. Chaque `git push` sur `main` redéploie automatiquement le site

### 3. URLs disponibles après déploiement

- `https://<votre-projet>.vercel.app/` → portfolio
- `https://<votre-projet>.vercel.app/formation` ou `/formation-hcd` → page d'inscription

### 4. Domaine personnalisé (optionnel)

Dashboard Vercel → Settings → Domains, ajoutez `oumarba.com` (ou équivalent).

## 🔄 Mise à jour

```bash
git add .
git commit -m "Mise à jour du contenu"
git push
```

Vercel redéploie automatiquement à chaque push.

## Page de vente des guides HCD (guides-hcd.html)

- URL : `/guides-hcd` (alias `/guides`), lien "Guides HCD" ajouté dans la nav de index.html (FR/EN).
- Achat : boutons WhatsApp (wa.me/221774181434) avec message pré-rempli, paiement manuel Wave / Orange Money, envoi du PDF à la main.
- `guides/` contient uniquement les extraits gratuits (6 p.) et les aperçus. Les PDF complets ne doivent JAMAIS être mis sur le site.

## Étude de cas CHARTer (index.html)
Carte « CHARTer, Sprint 2 » en tête de la section Études de cas (#charter), avec bouton « Lire l'étude de cas » (version longue repliable). Photo : recadrage sur Oumar uniquement, sans participante.
