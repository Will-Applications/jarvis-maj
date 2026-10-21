# Mises à jour de Jarvis

Ce dépôt contient seulement les fichiers de mise à jour de Jarvis (version des amis), jamais le code.

- `derniere.json` : la dernière version (numéro, nom du fichier, empreinte SHA-256, taille).
- `derniere.sig` : la signature Ed25519 de Will. Jarvis refuse toute fiche non signée par sa clé et tout
  installateur dont l'empreinte ne correspond pas exactement.

Jarvis vérifie ce dépôt au démarrage puis toutes les 6 heures, et n'installe une mise à jour que si
la personne clique sur « Installer ».
