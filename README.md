# Discord Role Icon Downloader

Récupère les icônes de rôles ou les emojis d'un serveur Discord et télécharge-les dans un ZIP.

**Utiliser l'outil :** https://TONPSEUDO.github.io/NOM-DU-DEPOT/

## Fonctionnalités

- Choix entre les **icônes de rôles** et les **emojis** du serveur (les emojis animés sont exportés en GIF)
- Liste les serveurs du compte et affiche les éléments de celui que tu choisis
- Sélection des icônes à télécharger (ou tout d'un coup)
- Export en ZIP, un fichier PNG par rôle, nommé d'après le rôle
- Fonctionne avec un token de compte Discord ou un token de bot
- Mode manuel : colle le JSON renvoyé par `GET /guilds/:id`

## Utilisation

1. Ouvre la page.
2. Choisis ce que tu veux télécharger (icônes de rôles ou emojis), puis colle ton token (ou passe sur l'onglet « JSON manuel »).
3. Clique sur **Charger les serveurs**, choisis un serveur, puis **Afficher**.
4. Coche les icônes voulues et clique sur **Télécharger le ZIP**.

## Sécurité

- Tout se passe dans ton navigateur : le token n'est envoyé qu'à `discord.com` et n'est jamais stocké ni transmis ailleurs. Tout le code tient dans un seul fichier, `index.html`, que tu peux relire.
- Un token de compte donne accès à l'intégralité du compte. Ne le partage jamais, avec personne.
- Utiliser un token de compte en dehors de l'application Discord va à l'encontre des conditions d'utilisation de Discord. Utilise-le à tes risques. Le mode token de bot ou le mode JSON manuel évitent ce problème.

## Limites

- Les icônes de rôles n'existent que sur les serveurs avec le **niveau 2 de boost** ou plus.
- Les rôles qui utilisent un emoji standard au lieu d'une image ne sont pas téléchargeables (ils sont seulement listés).

## Héberger sa propre copie

1. Fais un fork de ce dépôt (ou crée-en un et envoie `index.html`).
2. Va dans **Settings > Pages**.
3. Choisis **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis **Save**.

## Crédits

Fait par **Zhaak**. Rejoins le [serveur Discord](https://discord.gg/GRpCYzmtuJ).

Inspiré de [Discord Emoji Downloader](https://github.com/ThaTiemsz/Discord-Emoji-Downloader) de ThaTiemsz.

Ce projet n'est pas affilié à Discord Inc.
