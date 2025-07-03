# BUT: INTERROGER DE GROS VOLUMES DE DONNEES AVEC LE MOTEUR SQL clickhouse DB(chDB) ET ENSUITE LES MANIPULER 

---

Dans le notebook, nous pourrons remarquer comment s'est effectuée une requête sur de grosses bases de données avec le moteur **SQL chDB**, nous allons remarquer qu'on définit la logique métier avec **des clés primaires et clés étrangères**, tout en réalisant des **jointures sur des tables à partir des tables pivots**.
Et l'analyse sans statistique, s'est basée sur des aggrégations.

---

## 🗂️ Arborescence du projet

```
├── notebook/            # Notebook
├── .gitignore/          # Ignore les fichiers csv du notebook
├── README.md            # ce fichier
```