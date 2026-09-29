# Politique de confidentialité — InterBot

**Dernière mise à jour :** 2026-09-29

Cette politique décrit comment l’application Discord **InterBot** (« le Bot ») traite les données obtenues via l’API Discord (« API Data »), conformément à la [Politique pour les Développeurs Discord](https://discord.com/developers/docs/policies-and-agreements/developer-policy) et au RGPD / lois équivalentes.

## Responsable du traitement

L’opérateur du Bot (propriétaire de l’application Discord) est responsable du traitement. Contact : via le staff du serveur où le Bot est utilisé, ou le propriétaire de l’application sur le [Portail Développeur Discord](https://discord.com/developers/applications).

## Données collectées

Selon les fonctionnalités activées sur un serveur :

| Catégorie | Exemples | Finalité |
|-----------|----------|----------|
| Identifiants | ID utilisateur, serveur, salon, message | Fonctionnement, modération |
| Profil | Pseudo, avatar, surnom (historique) | Logs profil, sécurité |
| Contenu messages | Extraits pour logs d’édition/suppression et preuves | Modération |
| Vocaux | Métadonnées présence, logs Plume, enregistrements ponctuels | Modération / preuves |
| Confessions | Texte anonyme + auteur côté staff | Modération |
| Support / tickets | Contenu des tickets | Assistance |
| Progression | XP, niveaux, badges, minutes vocales | Gamification |
| Sanctions | Warns, mutes, bans, contextes | Sécurité du serveur |

Le Bot **ne revend pas** les API Data et ne les utilise pas pour de la publicité ciblée.

## Bases légales

- **Exécution du service** demandé par les administrateurs du serveur (fonctionnalités du Bot).
- **Intérêt légitime** (art. 6.1.f RGPD) pour la prévention et la constatation d’abus (sanctions, preuves).

## Conservation

| Données | Durée indicative |
|---------|------------------|
| Logs messages (salon Discord du bot) | ~7 jours |
| Cache messages (mémoire) | ~6 heures |
| Logs vocaux Plume (disque) | ~30 jours |
| Enregistrements audio orphelins | ~48 heures (supprimés après envoi au ticket) |
| Historique PP / Noms | jusqu’à 30 entrées / membre, effaçable via `/rgpd` |
| Sanctions / bans / contextes | durée nécessaire à la sécurité (intérêt légitime) |

## Sécurité

- Chiffrement **au repos** (AES-256-GCM) des fichiers JSON métier.
- Communications avec Discord via **TLS** (API / Gateway Discord).
- Accès aux données limité aux opérateurs du Bot et au staff habilité du serveur.

## Vos droits

Sur chaque serveur où le Bot est présent :

1. **`/rgpd`** — consulter un résumé des données vous concernant.
2. **`/rgpd`** — demander la suppression des données non nécessaires à la sécurité (niveaux, profils, badges, historiques PP/Noms, etc.).
3. Les données de **modération** (sanctions, bans) peuvent être conservées pour intérêt légitime.

Vous pouvez aussi contacter le staff du serveur ou le propriétaire de l’application.

## Mineurs

Des mécanismes de vérification d’âge / rôles Mineur–Majeur peuvent être activés par le serveur. Les moins de 13 ans (ou l’âge minimum légal local) ne doivent pas utiliser Discord ; le Bot s’aligne sur les règles Discord.

## Modifications

Cette politique peut être mise à jour. La date en tête de document fait foi. L’URL publique de cette page doit être renseignée dans le **Developer Portal** Discord (Privacy Policy URL).
