# Installer Aweep 1.0.1

macOS 26 ou plus récent · Mac Intel ou Apple silicon

1. Téléchargez `Aweep-1.0.1.dmg` depuis la release officielle du
   [canal Aweep](https://github.com/enrimerveille/aweep-releases/releases).
   Choisissez le DMG portant le numéro exact de la version souhaitée.
2. Ouvrez le DMG et glissez **Aweep** dans **Applications**.
3. Éjectez le DMG et ouvrez Aweep depuis Applications.
4. Si macOS bloque l’ouverture et propose cette autorisation pour Aweep :
   **Réglages Système → Confidentialité et sécurité → Ouvrir quand même**.
5. À l'ouverture manuelle, si « Masquer du Dock » et « Barre des menus » sont
   activés, Aweep ouvre son petit panneau depuis l'œil. Sinon, elle ouvre sa
   fenêtre principale. Le panneau donne accès à la fenêtre et aux Réglages.
   Le démarrage à la connexion reste silencieux ; cliquez alors sur l'œil.
   Un clic secondaire sur l’œil permet de quitter.
6. Dans **Réglages → Autorisation Aweep**, cliquez sur **Autoriser Aweep…**,
   puis confirmez la demande macOS. Une autorisation peut aussi être en attente
   dans **Réglages Système → Général → Ouverture et extensions**.
   Un compte administrateur ou son approbation peut être nécessaire.
7. Vérifiez **À propos : 1.0.1**, mode Système et autorisation vérifiée.
   Les choix « Barre des menus », « Masquer du Dock » et la recherche automatique
   de mises à jour sont activés par défaut. Les choix ultérieurs sont conservés.

Cette distribution manuelle est signée Apple Development, sans notarisation Apple.
L’ouverture n’est pas garantie sur chaque Mac : en cas de blocage persistant,
transmettez le message affiché et arrêtez l’installation. Une alerte de logiciel
malveillant ou d’app endommagée n’est pas une demande d’autorisation à ignorer.
Ne désactivez aucune protection macOS et ne supprimez pas la quarantaine.

Le lancement directement depuis le DMG, Downloads ou une copie secondaire
affiche une invitation à installer dans Applications et refuse le parcours
privilégié. Ouvrez la copie installée, puis fermez la copie source.

Pour une mise à jour manuelle, attendez qu’Aweep soit inactif, sans mode Éveillé,
Temporaire, Transport ou programmation. Quittez Aweep normalement avant de le
remplacer. Si Quitter est refusé, arrêtez l’installation et conservez l’app en place.
Si le helper change, retirez l’ancienne autorisation depuis l’ancienne app **avant**
de quitter et de remplacer le bundle, puis autorisez la nouvelle app.
Le [guide de mise à jour](UPDATE.md) détaille les deux parcours.
Vos préférences sont conservées hors du bundle.

Depuis Aweep 1.0.0 vers 1.0.1, le helper 1.0.0 est strictement identique :
conservez son autorisation. Depuis les versions 0.9.x ou 0.2.x, suivez le parcours
de changement de helper dans le guide de mise à jour.

Sur certaines configurations Intel/macOS 26, un repositionnement visible du
popover reste possible lors de sa première ouverture. Les ouvertures suivantes
fonctionnent normalement dans les essais rapportés ; cette réserve esthétique
est acceptée pour 1.0.1.

Procédure Apple : [ouvrir une app en sécurité](https://support.apple.com/fr-fr/102445).
