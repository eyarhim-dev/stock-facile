//q1.3://
//*disponible est stocké avec le type INTEGER 
//*date_ajout est stocké avec le type TEXT
//*AUTOINCREMENT : génère automatiquement un identifiant unique pour chaque nouvel enregistrement.
//*UNIQUE sur nom : empêche d'avoir deux catégories portant le même nom.
//*CHECK (prix >= 0) : interdit d'enregistrer un produit dont le prix est négatif.
//ON DELETE RESTRICT : empêche la suppression d’une catégorie si des produits sont encore associés à cette catégorie. Cela permet de préserver la cohérence des données.
//q4:On écrit deux apostrophes ('') pour que SQL affiche une seule apostrophe dans Huile d'olive.
//1.7:Le fichier `schema.sql` contient les commandes SQL permettant de créer les deux tables, leurs colonnes et leurs contraintes, sans les données.