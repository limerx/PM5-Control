# Politique de sécurité

[English](SECURITY.md) | **Français**

## État et périmètre

PM5 Control est expérimental. Aucune version de production prise en charge ni paquet d'installation n'est actuellement disponible. Utilisation uniquement avec autorisation explicite et dans le respect des politiques d'administration. Le projet n'accorde aucun privilège Android supplémentaire.

## Signalement

Pour les anomalies non sensibles, utiliser les issues du dépôt. Pour les vulnérabilités, demander un canal privé au mainteneur sans publier de détails d'exploitation. Si le signalement privé de vulnérabilités GitHub est activé, le privilégier.

Ne pas joindre d'identifiants RFID réels, de contenus de cartes, de dictionnaires privés, de secrets, de numéros de série ni de journaux non anonymisés.

## Priorités de vérification

- Isolation et contrôle d'accès HTTP, WebSocket et TCP locaux.
- Démarrage, déconnexion et arrêt sûrs des processus.
- Vérification des dépendances et de la provenance du code.
- Anonymisation des journaux et des données de test.

L'écoute sur une adresse locale ne constitue pas à elle seule une authentification ni une isolation contre les autres applications locales. Une commande terminée ou une empreinte de fichier identique ne suffit pas à prouver une relecture physique complète.
