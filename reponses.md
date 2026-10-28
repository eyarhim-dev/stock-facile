//q1.3://
//*disponible est stocké avec le type INTEGER 
//*date_ajout est stocké avec le type TEXT
//*AUTOINCREMENT : génère automatiquement un identifiant unique pour chaque nouvel enregistrement.
//*UNIQUE sur nom : empêche d'avoir deux catégories portant le même nom.
//*CHECK (prix >= 0) : interdit d'enregistrer un produit dont le prix est négatif.
//ON DELETE RESTRICT : empêche la suppression d’une catégorie si des produits sont encore associés à cette catégorie. Cela permet de préserver la cohérence des données.
//q4:On écrit deux apostrophes ('') pour que SQL affiche une seule apostrophe dans Huile d'olive.
//1.7:Le fichier `schema.sql` contient les commandes SQL permettant de créer les deux tables, leurs colonnes et leurs contraintes, sans les données.
//Q3.2
1/Si on écrit deux fois DatabaseHelper(), on obtient la même instance. Un seul objet est créé grâce au constructeur factory.
2/??= donne une valeur à une variable seulement si elle est null
3/Parce que onConfigure active les clés étrangères à chaque ouverture de la base, tandis que onCreate s’exécute seulement lors de sa création.
4/onCreate est appelé une seule fois, lorsque la base de données est créée pour la première fois.