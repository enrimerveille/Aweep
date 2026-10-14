# Aweep 1.0.1

Amélioration du positionnement du popover lors de la première ouverture.
Le contenu, Liquid Glass et les fonctions de l'application sont conservés.
Le helper 1.0.0 est réutilisé octet pour octet depuis Aweep 1.0.0.

## Limitation connue

Sur certaines configurations Intel/macOS 26, le popover peut effectuer un
repositionnement visible lors de sa première ouverture. Il reste utilisable et
les ouvertures suivantes fonctionnent normalement dans les essais rapportés.
Cette limitation est acceptée pour la publication 1.0.1 ; elle n'est pas
présentée comme entièrement corrigée.

Le premier lancement automatique a été observé sur Mac Pro 2019 / macOS 26.7.1 :
critère A PASS, stabilité visuelle B FAIL acceptée explicitement par l'utilisateur
le 14 octobre 2026. Les autres critères Intel C–J n'ont pas été relevés globalement
et ne sont pas présentés comme des PASS. Les essais ARM/macOS 27 ne remplacent pas
cette qualification Intel.

## Installation et mises à jour

macOS 26+ ; application Universal Intel et Apple silicon.
Signature Apple Development, non notarizée. Gatekeeper peut demander une
autorisation ou bloquer l'ouverture. Utilisez uniquement la procédure Apple
« Ouvrir quand même » si elle est proposée pour cette application.

Les mises à jour restent exclusivement manuelles par DMG. Sparkle détecte les
offres signées et ouvre la release officielle ; il n'installe pas Aweep.

Depuis Aweep 1.0.0, conservez l'autorisation du helper 1.0.0 inchangé. Attendez un
état inactif en mode Système, sans programmation ni Transport, puis quittez
normalement avant de remplacer Aweep dans Applications depuis le DMG.

Depuis 0.9.x ou 0.2.x, le helper change : retirez l'autorisation depuis l'ancienne
application inactive, attendez la confirmation, quittez, remplacez l'application,
puis autorisez le nouveau helper 1.0.0. En cas d'échec, arrêtez la migration.
Les préférences restent conservées hors du bundle.

[Installation](INSTALLATION.md) · [Mise à jour](UPDATE.md)
