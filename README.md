# 📖 Documentation du service 
## Lister les étudiants
### Point d'accès
> <span style="background-color:#85e4f2">GET https://service.ecoledudimanche.com/etudiants.php </span> 

### Paramètres
> Aucun

### Réponse
```xml
<etudiants>
   <etudiant>
      <id>5</id>
      <prenom>Nadine</prenom>
      <nom>Gia</nom>
   </etudiant>
</etudiants>
```
## Détailler un étudiant
### Point d'accès
> <span style="background-color:#85e4f2">GET https://service.ecoledudimanche.com/etudiant.php </span> 

### Paramètres
> etudiant={id} 
Le numéro est supérieur à zéro et est compris dans la liste des étudiants 

### Réponse
```xml
<etudiant>
   <id>5</id>
   <prenom>Nadine</prenom>
   <nom>Gia</nom>
   <programme>Informatique</programme>
</etudiant>
```

