# 🤖 Discord Bot - Documentation

Ce bot Discord multifonctions offre diverses commandes pour la modération, l'amusement, l'affichage d'informations et la gestion de serveur.

## 📋 Table des matières

- [Fonctionnalités](#fonctionnalités)
- [Commandes](#commandes)
  - [Configuration](#commandes-de-configuration)
  - [Modération](#commandes-de-modération)
  - [Administration](#commandes-administration)
  - [Utilitaires](#commandes-utilitaires)
  - [Fun](#commandes-fun)
  - [Animaux](#commandes-animaux)
  - [Vocal](#commandes-vocales)
  - [Stats](#commandes-de-statistiques)
- [Contribuer](#contribuer)
- [Licence](#licence)

## ✨ Fonctionnalités

- **Modération avancée**: Ban, kick, mute, clear, système d'avertissements
- **Administration avancée**: Système de ticket
- **Rôles automatiques**: Configuration de rôles pour les nouveaux membres et les bots
- **Commandes fun**: Combat, GIFs réactifs, faux tweets, memes, nitro, reverse, roulette, say, pileouface
- **Commandes d'animaux**: Images aléatoires de chats, chiens, lapins, etc.
- **Utilitaires**: Avatars, bannières, citations, recherche GitHub, générateur de mots de passe
- **Gestion de salons**: Lock, nuke, systèmes de bienvenue et d'au revoir
- **Commandes vocales**: Rejoindre, quitter et se déplacer entre salons vocaux
- **Interface intuitive**: Commandes slash entièrement intégrées à Discord

## 📝 Commandes

### Commandes de configuration

| Commande | Description | Utilisation |
|----------|-------------|-------------|
| `/autorole` | Configure le rôle automatique pour les nouveaux membres | `/autorole set @role` ou `/autorole remove` |
| `/botrole` | Configure le rôle automatique pour les bots | `/botrole set @role` ou `/botrole remove` |
| `/botrole welcome` | Active/désactive messages de bienvenue pour les bots | `/botrole welcome true/false` |
| `/goodbye` | Configure le salon d'au revoir | `/goodbye [salon]` |
| `/goodbye-off` | Désactive le système d'au revoir | `/goodbye-off` |
| `/welcome` | Désactive le système d'au revoir | `/welcome [salon]` |
| `/welcome-off` | Désactive le système d'au revoir | `/welcome-off` |
| `/logs` | Configure les salons de logs pour la modération et les messages | `/logs [type] [salon]` |


### Commandes de modération

| Commande | Description | Utilisation |
|----------|-------------|-------------|
| `/ban` | Bannit un membre du serveur | `/ban @utilisateur [raison]` |
| `/kick` | Expulse un membre du serveur | `/kick @utilisateur [raison]` |
| `/mute` | Rend temporairement muet un membre | `/mute @utilisateur temps [raison]` |
| `/clear` | Supprime un nombre spécifié de messages | `/clear nombre [salon]` |
| `/clearwarns` | Efface tous les avertissements d'un utilisateur | `/clearwarns @utilisateur [raison]` |
| `/lock` | Verrouille un salon pour empêcher l'envoi de messages | `/lock [salon] [raison]` |
| `/nuke` | Nuke le salon en le supprimant et le recréant à l'identique | `/nuke` |

### Commandes administration

| Commande | Description | Utilisation |
|----------|-------------|-------------|
| `/ticket setup` | Configurer le système de tickets | `/ticket setup [salon] [rôle] [catégorie] [description]` |
| `/ticket close` | Fermer un ticket manuellement | `/ticket close` |
| `/ticket add` | Ajouter un utilisateur au ticket actuel | `/ticket add [membre]` |
| `/ticket remove` | Retirer un utilisateur du ticket actuel | `/ticket remove [membre]` |
| `/ticketstats` | Affiche les statistiques des tickets du serveur | `/ticketstats` |
| `/transcript` | Générer une transcription du ticket actuel | `/transcript [salon]` |

### Commandes utilitaires

| Commande | Description | Utilisation |
|----------|-------------|-------------|
| `/avatar` | Affiche l'avatar d'un utilisateur | `/avatar [membre]` |
| `/banner` | Affiche la bannière d'un utilisateur | `/banner [membre]` |
| `/createquote` | Ajoute une citation personnalisée | `/createquote texte auteur` |
| `/deletequote` | Supprime une citation personnalisée | `/deletequote texte auteur` |
| `/github` | Affiche des projets GitHub aléatoires | `/github [nombre] [min_stars] [max_stars] [langage]` |
| `/help` | Affiche les commandes disponibles | `/help [commande]` |
| `/password` | Génère un mot de passe aléatoire et sécurisé | `/password [longueur] [options]` |
| `/quote` | Affiche une citation aléatoire | `/quote [auteur]` |
| `/listquotes` | Affiche toutes les citations avec pagination et filtre par type | `/listquotes` |
| `/remind` | Affiche toutes les citations avec pagination et filtre par type | `/remind [temp]` |
| `/weather` | Affiche la météo d'une ville | `/weather [ville/pays]` |

### Commandes fun

| Commande | Description | Utilisation |
|----------|-------------|-------------|
| `/de` | Lance un dé à 6 faces | `/de` |
| `/faketweet` | Crée un faux tweet | `/faketweet texte` |
| `/fight` | Lance un combat entre deux membres | `/fight @adversaire` |
| `/gif` | Envoie un GIF de réaction anime | `/gif reaction` |
| `/meme` | Envoie un meme aléatoire | `/meme` |
| `/nitro` | Envoie un faux cadeau Nitro (farce) | `/nitro` |
| `/reverse` | Inverse le texte donné | `/reverse [message]` |
| `/roulette` | Joue à la roulette russe | `/roulette [membre]` |
| `/say` | Faire dire un message au bot | `/say [message]` |
| `/pileouface` | Joue à pile ou face | `/pileouface` |

### Commandes animaux

| Commande | Description | Utilisation |
|----------|-------------|-------------|
| `/cat` | Affiche une image aléatoire de chat | `/cat` |
| `/dog` | Affiche une image aléatoire de chien | `/dog` |
| `/fox` | Affiche une image aléatoire de renard | `/fox` |
| `/duck` | Affiche une image aléatoire de canard | `/duck` |
| `/bunny` | Affiche une image aléatoire de lapin | `/bunny` |
| `/panda` | Affiche une image aléatoire de panda | `/panda` |


### Commandes vocales

| Commande | Description | Utilisation |
|----------|-------------|-------------|
| `/join` | Fait rejoindre le salon vocal au bot | `/join [salon]` |
| `/leave` | Fait quitter le salon vocal au bot | `/leave` |
| `/move` | Déplace le bot vers un autre salon vocal | `/move salon` |

### Commandes de statistiques

| Commande | Description | Utilisation |
|----------|-------------|-------------|
| `/botstats` | Affiche les statistiques du bot | `/botstats` |
| `/serverinfo` | Affiche les statistiques du serveur | `/serverinfo` |
| `/userinfo` | Affiche les statistiques d'une personne | `/userinfo [membre]` |


## 📂 Structure des données

Le bot stocke ses données dans le dossier `./data` avec la structure suivante:

- `./data/config/` - Fichiers de configuration par serveur
- `./data/warns/` - Avertissements des utilisateurs
- `./data/quote/` - Citations personnalisées
- `./data/remind/` - Pour les rappelles
- `./data/ticket/` - Pour les tickets

## 🤝 Contribuer

Les contributions sont les bienvenues! Pour contribuer:

1. Forkez le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/amazing-feature`)
3. Committez vos changements (`git commit -m 'Add some amazing feature'`)
4. Poussez vers la branche (`git push origin feature/amazing-feature`)
5. Ouvrez une Pull Request

## 📄 Licence

Ce projet est sous licence [MIT](LICENSE).

---

Créé avec ❤️ par Patpat