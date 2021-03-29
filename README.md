# script_backup
Script récupérant la date actuel et place le backup dans le dossier correspondant :
{partie web + db, convertit en tar.gz}


Avant de lancer :

-Pour que les sauvegardes se place dans la bonne année/mois, créer les repertoires années (2021, 2022, 2023...) puis les mois à l'interrieur de chacun (01,02,03...)
-Adapter les chemins dans le script
-Pour décomposer le resultat : tar -xvf 
-L'archive se re-décompose en 2 parties distinctes

