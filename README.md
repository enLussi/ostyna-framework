# Framework Ostyna

Framework php léger et simple

## 1. Mise en place du projet

Télécharger la dernière version stable (à ce jour sur la branche dev) et initialiser un dépot git.
Installer le package de base nécessaire:
```sh
composer require ostyna/core
```

De la même manière et selon vos besoins, vous pouvez installer d'autres dépendances:
```sh
composer require ostyna/orm
composer require ostyna/sing
```

Une fois vos dépendances installer, dupliquer et renommer le dossier .env en .env.local en complétant avec les informations de votre base de données si vous en utilisez une.
Le framework ne créera pas la base de données automatiquement.



