# Mettre à jour Aweep 1.0.0

La recherche automatique est activée par défaut. Vous pouvez la désactiver dans
les Réglages ; OFF reste OFF au prochain lancement. Une recherche manuelle reste
possible. Aweep vérifie le flux signé et accepte seulement la release officielle.
Une erreur de serveur, de flux ou de signature n’autorise aucune installation.

« Télécharger le DMG » ouvre la page GitHub de la version détectée. Choisissez
`Aweep-X.Y.Z.dmg` dans ses assets. Aweep ne remplace pas automatiquement l’app.

## 0.9.0 → 0.9.1 : helper identique

Les deux versions publiées embarquent exactement le même helper, version 0.9.0.
Il n’est pas nécessaire de retirer puis de renouveler son autorisation pour cette
paire. La version 0.9.1 de l’interface accepte ce helper 0.9.0 authentifié.

1. Depuis 0.9.0, vérifiez les mises à jour et ouvrez la release officielle 0.9.1.
2. Téléchargez son DMG. Revenez en mode Système, sans programmation ni Transport
   actif, et attendez un état vérifié.
3. Quittez Aweep normalement, via son menu ou le clic secondaire sur l’œil.
   Si la fermeture est refusée, arrêtez la mise à jour.
4. Remplacez Aweep dans Applications depuis le DMG ; éjectez le DMG.
5. Ouvrez Aweep depuis Applications. Vérifiez 0.9.1, autorisation valide et vos
   préférences, y compris le choix de recherche automatique.

Ce parcours a été qualifié physiquement le 12 octobre 2026 sur Mac Pro
Intel / macOS Tahoe 26.7.1. Cela ne qualifie pas le changement de helper de 1.0.0.

## Vers 1.0.0 : helper différent

Le passage de 0.9.x ou d'une quotidienne 0.2.x à 1.0.0 change le helper. L’app
1.0.0 attend un helper authentifié de majeure 1. Le helper 0.9.0 ou 2.x ne doit
pas être réutilisé. L'ancien helper doit être retiré **avant** de remplacer l'app.

1. Dans l’ancienne Aweep, revenez en mode Système et vérifiez l’absence de
   programmation, de Transport et d’action en cours. Un état non vérifié impose
   l’arrêt de la mise à jour.
2. Dans ses Réglages, choisissez **Retirer l’autorisation Aweep**, confirmez et
   attendez que l’ancienne autorisation soit retirée. Si l’action échoue ou reste
   indisponible, conservez l’app et signalez le message.
3. Quittez normalement l’ancienne app, puis remplacez-la dans Applications.
4. Lancez la nouvelle copie et choisissez **Autoriser Aweep…**. Confirmez les
   autorisations demandées par macOS, puis vérifiez la version et l’état.

Les préférences métier restent dans le même domaine hors du bundle. N’effacez
aucun service, journal ou fichier de préférences. N’utilisez aucune transaction
Recovery ni commande de suppression. Si Gatekeeper bloque l’ouverture, suivez
le [guide d’installation](INSTALLATION.md).
