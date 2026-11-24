# Budget Kin–Abidjan

Application web installable (PWA) de suivi budgétaire personnel : revenus et charges entre Kinshasa et Abidjan, avis sur une dépense, projets, journal des dépenses et recettes.

- Aucune donnée personnelle dans ce dépôt : tout est saisi dans l'application et reste sur le téléphone.
- Mot de passe optionnel : les données sont alors chiffrées (AES-GCM, clé dérivée par PBKDF2) avant d'être enregistrées.
- Déverrouillage par Face ID ou empreinte (WebAuthn) une fois le mot de passe actif.
- Fonctionne hors ligne grâce au service worker.

Installation : ouvrir le site dans Safari (iPhone) ou Chrome (Android), puis « Sur l'écran d'accueil » / « Ajouter à l'écran d'accueil ».
