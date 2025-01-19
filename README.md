# Contexte :
**STRACA SA**, est une société créée en 2004 basée au bénin et qui intervient dans les domaines du transport,
de la logistique et du commerce. De façon spécifique, la société intervient dans le transport
d’agrégats (sable gravier, concassés…) et la location de véhicules (légers et poids lourds).
Les agrégats sont chargés des sites d’expéditions (carrière, bord de mer, zone
marécageuses…) et sont convoyés vers les sites de réception (chantier de construction de
routes) pour différents clients. Ces clients opèrent notamment dans le domaine des travaux
publics (construction d’infrastructures routières, d’aménagement du cadre de vie).

# Note:

Ce projet académique vise à mettre en place un tableau de bord interactif permettant de suivre et d'analyser les performances de l'entreprise.

# Outil utilisé: Power BI

# Objectif: 

Afin de répondre aux exigences de l’entreprise et de faciliter la prise de décisions stratégiques, la direction demande la création de tableaux de bords dynamiques. Ces derniers
doivent permettre un suivi efficace des activités, en offrant une vision claire et précise des données relatives de la logistique. 

Deux principaux indicateurs de performance ont été définis :
1. Quantité en cubage/tonnage :
 - Cet indicateur permettra de suivre l’évolution des volumes expédiés et réceptionnés.
2. Nombre de voyages effectués :
 - Cet indicateur permet de suivre l’activité des camions et des conducteurs.

Les données des indicateurs seront exploitées selon différents filtres, notamment :
- La date (sur toute la période ou sur une date donnée).
- Le site d’expédition ou de réception.
- La quantité de produits transportée (cubage ou tonnage).
- La possibilité de choisir un nombre N pour afficher les N conducteurs les plus performants.

# Quelques demonstrations du travail:
- Je vous joins le fichier Power BI si jamias ça vous inspire d'en savoir plus: voir le fichier Tableaux de bords.pbix ci-joint.
- Voyons quelque analyse du Tableau:

![image](https://github.com/Hadad-Ahmed-Ali/Tableaux-des-bord/blob/main/1.png)
- Dans le premier graphique, on a filtré les sites de réception et la quantité en tonnage pour visualiser cette quantité selon les différents sites de réception. Aucune date n’a été sélectionnée sur le filtre "Choisir la date de l’opération", ce qui signifie que nous regardons l’ensemble de la période. Cela permet de savoir si la quantité de produit réceptionnée est du type Concassé ou Boue. Par exemple, nous voyons que le site d’**Adounko Nord** a reçu **5 016 tonnes de Concassé**, et le site **Ouèssè SGDS_GN** a reçu **1 083 tonnes de Boue**. Sur toute la période, la **quantité totale de produits expédiés/réceptionnés en tonnage** est de **12 823,12 tonnes**.
- Dans le deuxième graphique, aucune date n’a non plus été sélectionnée, donc nous regardons l’ensemble de la période. Il montre que les **camions de l’entreprise** ont effectué **1 089 voyages**, soit 70,03 % des voyages, contre **466 voyages** (29,97 %) effectués par **les camions loués**.
- Dans le troisième graphique, aucune date n’a été sélectionnée, donc nous sommes toujours sur l’ensemble de la période. Nous avons appliqué un filtre **"Top N conducteurs avec plus de voyages"** pour voir les **10 conducteurs** ayant effectué le plus de voyages sur toute la période. On peut voir que le premier conducteur est **ZANNOU JOEL**, avec **72 voyages** effectués.
- Dans le quatrième graphique, pareillement, aucune date n’a été sélectionnée, et nous visualisons le nombre de voyages reçus pour chaque site de réception. Par exemple, le site **GER Ouèdo** a reçu le plus grand nombre de voyages, avec **531 voyages**, sur toute la période.

![image](https://github.com/Hadad-Ahmed-Ali/Tableaux-des-bord/blob/main/4.png)

Dans ce même tableau, on applique le même principe d’analyse, mais cette foisci, le filtre est effectué sur le **site d’expédition** au lieu du site de réception.
De plus, la mesure de la quantité de produit est basée sur le **cubage** (quantité en mètres cubes) au lieu du tonnage. Aucune date n’a été filtrée, donc nous
restons sur l’ensemble de la période.

![image](https://github.com/Hadad-Ahmed-Ali/Tableaux-des-bord/blob/main/5.png)

Toujours dans le même principe d’analyse, cette fois nous avons choisi une date pour voir les résultats correspondants, notamment **"mercredi 15 mars 2023"**:
- **210 mètres cubes** de **sable continental** et **39 mètres cubes** de **sable marin** ont été expédiés depuis le site **PK10** (premier graphique).
- Les **camions de l’entreprise** ont effectué **112 voyages**, contre **15 voyages** effectués par les **camions privés** (graphique 2).
- Le troisième graphique montre les **10 conducteurs** ayant effectué le plus de voyages, avec en **première position ZANNOU JOEL** qui a effectué, **46 voyages** ce jour-là.
- En ce jour-là, trois sites ont eu des expéditions de produits : le site **Carrière SATOM, Industries Agonsoudja et PK10**, le site **Carrière SATOM** ayant eu le plus grand nombre d’opérations, avec **78 voyages** effectués.
