# Mettre à jour Aweep

Aweep peut signaler une nouvelle version et ouvrir sa page GitHub. **La mise à jour reste manuelle** : téléchargez le nouveau DMG et remplacez l'application dans **Applications**.

**Avant toute mise à jour :** revenez au mode **Système**, vérifiez qu'aucun Transport, maintien éveillé ou programmation n'est actif, puis suivez le parcours adapté ci-dessous. Si cet état ne peut pas être vérifié, arrêtez la procédure. Vos préférences sont normalement conservées.

## De 1.0.0 à 1.0.1

Le service privilégié (helper) est inchangé : **conservez son autorisation**.

1. Quittez normalement Aweep 1.0.0.
2. Ouvrez le [DMG 1.0.1](https://github.com/enrimerveille/aweep-releases/releases/download/1.0.1/Aweep-1.0.1.dmg) et remplacez Aweep dans **Applications**.
3. Lancez la nouvelle version et vérifiez l'autorisation ainsi que vos préférences.

## Depuis 0.9.x ou 0.2.x vers 1.0.1

Ces versions utilisent un ancien helper. **Retirez son autorisation avant de remplacer Aweep.**

1. Dans l'ancienne application inactive, ouvrez les Réglages et choisissez **Retirer l'autorisation Aweep**. Attendez la confirmation effective.
2. Quittez normalement l'ancienne application.
3. Remplacez Aweep dans **Applications** depuis le DMG 1.0.1.
4. Ouvrez Aweep 1.0.1 puis choisissez **Autoriser Aweep…** et confirmez les demandes de macOS.

Si le retrait ou la fermeture échoue, **arrêtez la mise à jour** : ne remplacez pas l'application et ne tentez pas d'effacer manuellement le helper.

## De 0.9.0 à 0.9.1 (historique)

Le helper de ces deux préversions est identique : quittez Aweep après avoir vérifié l'état inactif, remplacez-la depuis le DMG 0.9.1, puis relancez-la. Aucune nouvelle autorisation n'est normalement nécessaire.

Pour les difficultés de premier lancement et Gatekeeper, consultez le [guide d'installation](INSTALLATION.md).
