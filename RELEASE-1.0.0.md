# Aweep 1.0.0

Première version 1.0.0 d’Aweep, application native macOS pour gérer l’éveil et
programmer la veille ou l’extinction de votre Mac.

Modes Système, Éveillé et Temporaire ; Transport sur les portables compatibles.
Interface française et anglaise, apparence claire/sombre, barre des menus,
fenêtre et option pour masquer le Dock. Vos préférences restent conservées.

Les mises à jour sont détectées et vérifiées avec Sparkle. Le téléchargement du
DMG et le remplacement de l’app sont manuels. Une offre précédente est effacée
lorsqu’une nouvelle vérification échoue ; aucun ancien lien n’est alors proposé.

**macOS 26+ · Intel et Apple silicon · Apple Development · non notarizé.**
Cette signature n’est pas Developer ID ; Gatekeeper peut bloquer le lancement.
Consultez [l’installation](INSTALLATION.md) et [la mise à jour](UPDATE.md).
L'ouverture manuelle affiche le petit panneau si le Dock est masqué et la barre
des menus activée ; sinon, elle affiche la fenêtre principale. Le démarrage à la
connexion reste silencieux. Le sélecteur Liquid Glass et les transitions respectent
Reduce Motion ; l'en-tête reste stable lorsque le contenu change de hauteur.

**Depuis 0.9.1 : le helper change de 0.9.0 à 1.0.0.** Dans l'ancienne app en mode
Système, sans programmation ni Transport, retirez l'autorisation Aweep et attendez
sa confirmation **avant de quitter et remplacer** l'app. Lancez ensuite 1.0.0 et
autorisez son nouveau helper. Si le retrait ou la fermeture échoue, arrêtez la mise
à jour et conservez l'ancienne app. Aucun effacement manuel de service n'est requis.
Le [guide](UPDATE.md) détaille ce parcours et les conditions d'arrêt.

Téléchargez `Aweep-1.0.0.dmg` depuis cette release. Les archives ZIP et DMG sont
signées EdDSA et accompagnées de checksums et d’un manifeste public expurgé.
