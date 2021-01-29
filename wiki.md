# Project Wiki
## Delete
Afin de pouvoir supprimer un project wiki, il faut supprimer son repo Git (caché)

Trouver le repo GIt derrière le wiki :

``` 
az devops wiki list --project <MonProjet>
``` 

Récupérer le repository id (ex : 2c9047e3-ecb9-4913-b51e-893bc5a3e610)

Suppression du repos
```
az repos delete --id 2c9047e3-ecb9-4913-b51e-893bc5a3e610 --project <MonProjet>
```
