# Projet TinyPet

Ce projet a été réalisé par SALIFOU Moussa, BLANCHET Alexandre, ROBERT Matthias

|      ACTION          |          METHODE|REALISÉ|
|----------------|-------------------------------|-----------------------------|
|Créer une pétition|addPetition        |✅            |
|Signer une pétition|signPetition       |✅    |
|Lister les pétition signer par un utilisateur|getMyPetitionsSign|✅|
|Top 100 des pétitions|getTopPetition|✅|
|Recherche des pétitions par "tag"|getPetitionByTag|✅|

## Schéma de l'entité Petition dans le datastore

|      FIELD          |          TYPE|USAGE|
|----------------|-------------------------------|-----------------------------|
|key|String|Identifiant unique timestamp+owner |
|titre|String|Titre de la pétition|
|body|String|Contenu de la pétition|
|owner|String|Auteur de la pétition|
|date|Date|Date de publication|
|nbSignatory|Integer|Nombre de signature|
|Signatory|Array|Liste des signataires|
|tag|String|Tag|

Le lien vers l'application : https://tinypet-349718.ey.r.appspot.com/
