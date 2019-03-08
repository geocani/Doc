# Installation Dolibarr sur un NAS Synology.

# Chapitres:

<details> 
  <summary>1 : Acceder au serveur </summary>

## Connexion au serveur.

1. Ouvrire un navigateur web.
2. Acceder à l'adresse 192.168.2.45:500
3. Entrer son pass et son login.

<a href="print-1.png"><img src="print-1.png" alt="drawing" width="500"/></a>

</details>

<details> 
  <summary>2 : Créer un dossier racine </summary>

## Créer un dossier racine.

1. Cliquer sur ==file station==.
2. Sélectionner l'option ==web==.
3. Créer un nouveau dossier avec le nom souhaité.

<a href="print-2.png"><img src="print-2.png" alt="drawing" width="500"/></a>
<a href="print-3.png"><img src="print-3.png" alt="drawing" width="500"/></a>

</details>

<details> 
  <summary>3 : Créer un virtual host </summary>

## Créer un virtual host.

1. Ouvrire le ==menu principal==. 
2. Ouvrire ==web sation==.
3. Ouvrire la gestion des ==virtual host== dans le menu de gauche.
4. ==Créer== un nouvel host.
5. Cocher ==basé sur le nom==, entrer un ==nom d'hôte== et cocher le ==port 80/443==
6. Ajouter le dossier racine ==(chapitre 2).==
7. Renseigner le serveur principal ==HTTP== et la version de ==PHP.==

<a href="print-4.png"><img src="print-4.png" alt="drawing" width="500"/></a>
<a href="print-5.png"><img src="print-5.png" alt="drawing" width="500"/></a>
<a href="print-6.png"><img src="print-6.png" alt="drawing" width="500"/></a>

</details>

<details> 
  <summary>4 : Modifier les autorisations du dossier source </summary>

## Modifier les autorisations du dossier source.

1. Retourner dans ==file station==.
2. Cliquer droit sur le dossier source et sélectionner les ==propriétés==.
3. Cliquer sur ==permission==.
4. Selectionner ==http==.
5. Cliquer sur ==modifier==.
6. Activer les autorisations en lecture et écriture.

<a href="print-7.png"><img src="print-7.png" alt="drawing" width="500"/></a>
<a href="print-8.png"><img src="print-8.png" alt="drawing" width="500"/></a>
<a href="print-9.png"><img src="print-9.png" alt="drawing" width="500"/></a>

</details>

<details> 
  <summary>5 : Importer Dolibarr </summary>

## Modifier les autorisations du dossier source.

1. Retourner dans ==file station==, ouvrire le dossier source et y importer Dolibarr

<a href="print-10.png"><img src="print-10.png" alt="drawing" width="500"/></a>

</details>

<details> 
  <summary>6 : Créer la base de donnée </summary>

## Créer la base de donnée.

1. 

</details>

