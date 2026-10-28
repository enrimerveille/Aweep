# Installer Aweep

**macOS 26+ · Intel et Apple silicon**

**Aweep est déjà installée ?** Consultez le [guide de mise à jour](UPDATE.md) avant de remplacer l’application.

1. [Téléchargez Aweep 1.1.1](https://github.com/enrimerveille/Aweep/releases/download/1.1.1/Aweep-1.1.1.dmg).
2. Ouvrez le DMG, puis glissez **Aweep** dans **Applications**. Éjectez le DMG.
3. Ouvrez Aweep depuis **Applications**. Si macOS bloque l’ouverture, suivez la procédure de sécurité ci-dessous.
4. Dans les Réglages d'Aweep, cliquez sur **Autoriser Aweep…** et confirmez l'autorisation macOS. Si nécessaire, consultez **Réglages Système → Général → Ouverture et extensions**. Une approbation administrateur peut être requise.

## Autorisation de sécurité macOS

Aweep est signée **Apple Development, sans notarisation Apple**. macOS peut bloquer son premier lancement.

Si macOS propose cette possibilité pour Aweep, ouvrez **Réglages Système → Confidentialité et sécurité → Ouvrir quand même**, conformément à la [procédure Apple](https://support.apple.com/fr-fr/102445).

En cas de blocage persistant ou d'alerte indiquant qu'une application est endommagée ou malveillante, interrompez l'installation. Ne désactivez pas Gatekeeper et ne supprimez pas la quarantaine.

## Utilisation

L'œil dans la barre des menus ouvre Aweep ; ses Réglages sont accessibles depuis le panneau ou la fenêtre principale. Sur les configurations avec Dock masqué, l'ouverture manuelle présente le panneau. Le démarrage à la connexion est silencieux.

### Responsables de l’éveil et écran

La fenêtre et le panneau affichent les applications ou services qui demandent à maintenir le Mac éveillé ou l’écran allumé. Dépliez « Responsables de l’éveil » pour consulter leurs effets et motifs déclarés. Lorsqu’un service agit pour une application non identifiée, Aweep le signale sans deviner son origine. Les événements programmés restent présentés séparément.

En mode Éveillé ou Temporaire, cochez « Garder l’écran allumé » pour demander à macOS d’éviter l’extinction de l’écran due à l’inactivité. L’option est désactivée par défaut. Son choix est mémorisé, mais aucune session ne démarre au lancement. Le retour à Système, le passage à Transport, la fin de la durée et la fermeture d’Aweep libèrent cette demande.

Cette option ne rallume pas un écran déjà éteint, ne déverrouille pas une session et ne garantit pas l’absence de verrouillage automatique. L’économiseur, la demande de mot de passe et le verrouillage volontaire restent soumis à macOS et à vos réglages. Aucune permission supplémentaire n’est nécessaire.

## Dépannage

Sur certains Mac Intel sous macOS 26, la petite flèche reliant le panneau à la barre des menus peut être déformée lors de la première ouverture. Fermez le panneau puis rouvrez-le en cliquant sur l'œil.

Si un problème d'autorisation ou de lancement persiste, conservez le message macOS exact et arrêtez la procédure plutôt que de contourner une protection.
