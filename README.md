# Chez Nous 89270

Site web du restaurant **Chez Nous**, réalisé avec le framework Astro et déployé automatiquement sur Netlify.

**Découvrez le site :** [cheznous89270.fr](https://cheznous89270.fr)

***

## Fonctionnalités

- Design responsive adapté à tous les appareils
- Contenu généré statiquement pour des performances optimales
- Consultation des menus au format PDF
- Galeries photo pour mettre en valeur le restaurant
- Intégration automatique quotidienne de l'**ardoise du jour** publiée sur Instagram
- Affichage d'une carte interactive
- Optimisation des images (WebP, lazy-loading)
- Administration du contenu éditorial via [PageCMS](https://pagescms.org/)

***

## Structure du projet

```text
/
├── public/
├── src/
    ├── assets
    ├── components
    ├── content
    ├── layouts
    ├── lib
    ├── pages
    ├── scripts
    ├── styles
    └── types
```

***

## Déploiement planifié

Un déploiement est automatiquement déclenché chaque jour à **12h (heure de Paris)** via une GitHub Action, afin de récupérer et afficher l'ardoise du jour publiée sur Instagram.

***

## Pour commencer

1. Forkez ce dépôt, ou utilisez-le comme base pour un nouveau projet.
2. Exécutez les commandes suivantes dans votre terminal :

```bash
# Cloner le dépôt
git clone https://github.com/cheznous89270/cheznous.git

# Naviguer dans le répertoire du projet
cd cheznous

# Installer les dépendances
npm install

# Démarrer le serveur de développement
npm run dev
```

***

## Licence

Ce projet est distribué sous la **licence MIT**. Le code source est librement réutilisable dans les conditions de cette licence.

> ⚠️ Les contenus liés à l'établissement (textes, images, horaires, ardoise du jour, menus, etc.) restent la propriété exclusive du restaurant **Chez Nous**. Leur utilisation ou reproduction est interdite sans autorisation préalable.

***

## Crédits

### Framework

- **Astro** — [astro.build](https://astro.build/)

### Hébergement & déploiement

- **Netlify** — [netlify.com](https://www.netlify.com/)

### CMS

- **PageCMS** — [pagescms.org](https://pagescms.org/)

***

**Développeur web :** [hostoftheshell](https://github.com/hostoftheshell)

**Dernière mise à jour :** février 2026

***
