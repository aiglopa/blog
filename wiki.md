## Project Wiki
# Delete
Afin de pouvoir supprimer un project wiki, il faut supprimer son repo Git (caché)

Afficher les informations du repos :
``` 
az repos show --wiki ABC.wiki --project <MonProjet>
```

Suppression du repos
```
az repos delete --id 2c9047e3-ecb9-4913-b51e-893bc5a3e610 --project <MonProjet>
```
