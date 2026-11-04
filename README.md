# TVA PRO

Application Windows locale combinée réunissant :

- **Calculatrice TVA** : calcul HT, TVA, TTC, historique, export CSV et PDF ;
- **TVA Manager** : gestion multi-sociétés, import comptable, règles TVA, calcul mensuel, historique et rapports.

Les deux espaces utilisent des stockages JSON séparés afin de préserver leurs données et leurs paramètres existants. Développée par / Mohamed Amine.

## Démarrage

```powershell
npm.cmd install
npm.cmd start
```

## Exécutable Windows

```powershell
npm.cmd run dist
```

## Périmètre actuel

La version inclut une base locale séparée par société, la création/archivage de sociétés, l’import `.xlsx`, `.xls` et `.csv`, la prévisualisation, la détection de taux mémorisés, le tableau des écritures, la modification du sens et du taux, la validation, le calcul mensuel collectée − déductible − crédit antérieur, l’historique, les règles mémorisées, le mode clair/sombre et les exports CSV/Excel.

Elle inclut également l’espace Calculatrice TVA avec calcul depuis HT, TVA ou TTC, taux personnalisés, historique séparé, export CSV, export PDF et copie des résultats.

Les suggestions sont déterministes et hors ligne dans cette version : règles manuelles et historique priorisés, puis statut « À vérifier ». Elles ne constituent pas une décision fiscale automatique. Le dossier de données local est géré par Electron dans le profil utilisateur Windows.
