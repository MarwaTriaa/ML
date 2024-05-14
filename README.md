# ML
Patients diagnostiqués diabétiques

Notre dataset représente dix années (1999-2008) de soins cliniques dans 130 hôpitaux américains et réseaux de prestation intégrés. Chaque ligne concerne les dossiers hospitaliers de patients diagnostiqués diabétiques, qui ont subi des examens de laboratoire, des médicaments et sont restés jusqu'à 14 jours. L'objectif est de déterminer la réadmission précoce du patient dans les 30 jours suivant sa sortie. Le problème est important pour les raisons suivantes. Malgré des preuves de grande qualité démontrant de meilleurs résultats cliniques pour les patients diabétiques bénéficiant de diverses interventions préventives et thérapeutiques, de nombreux patients ne les reçoivent pas. Cela peut être partiellement attribué à la gestion arbitraire du diabète en milieu hospitalier, qui ne parvient pas à contrôler la glycémie. L’incapacité à fournir des soins appropriés pour le diabète augmente non seulement les coûts de gestion pour les hôpitaux (à mesure que les patients sont réadmis), mais a également un impact sur la morbidité et la mortalité des patients, qui peuvent être confrontés à des complications associées au diabète.

Il comprend plus de 50 features représentant les résultats des patients et des hôpitaux. Les informations ont été extraites de la base de données pour les rencontres répondant aux critères suivants. (1) Il s’agit d’une rencontre avec un patient hospitalisé (une admission à l’hôpital). Il s’agit d’une rencontre diabétique, c’est-à-dire une rencontre au cours de laquelle n’importe quel type de diabète a été enregistré dans le système comme diagnostic. La durée du séjour était d'au moins 1 jour et d'au plus 14 jours.  Des tests de laboratoire ont été effectués lors de la rencontre. (5) Des médicaments ont été administrés pendant la rencontre. Les données contiennent des attributs tels que le numéro du patient, la race, le sexe, l'âge, le type d'admission, le temps passé à l'hôpital, la spécialité médicale du médecin admis, le nombre de tests de laboratoire effectués, le résultat du test HbA1c, le diagnostic, le nombre de médicaments, les médicaments contre le diabète, le nombre de patients ambulatoires., visites d'hospitalisation et d'urgence au cours de l'année précédant l'hospitalisation, etc.

To do : prédire la valeur de « readmitted »

Readmitted : Jours avant la réadmission des patients hospitalisés. Valeurs : <30 si le patient a été réadmis dans moins de 30 jours, >30 si le patient a été réadmis dans plus de 30 jours et Non pour aucun enregistrement de réadmission

Nous avons utilisé 6 modeles de ML : 
Logistic regression
Decision Tree
Random Forests
SVM
KNN
ACP
