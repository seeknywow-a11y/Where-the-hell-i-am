# Anomalies retenues — mur est

Les anomalies E01 à E13 sont retenues. La colonne « Postes » fixe leur plage de tirage : **1–8** par défaut. Le changement se produit uniquement sur le mur est : tableau d'informations, porte vers le poste suivant, signalétique ou fenêtre latérale floutée. Le colis et les autres murs fournissent parfois la référence de comparaison, mais restent dans leur état normal pour cette anomalie.

E05 commence au poste 2 parce que deux plaques changent de place. E04, E06 et E07 s'arrêtent au poste 7 parce qu'il n'existe ni poste suivant, ni porte et fenêtre est donnant sur un neuvième poste au poste 8. Une seule anomalie peut être active dans un poste, et un même identifiant ne peut pas revenir deux fois pendant la même tentative.

Pour les propositions qui utilisent des données de suivi, le tableau est pourrait recevoir une fiche amovible liée au colis en cours, à côté d'un plan de routage permanent. Cette composition reste une piste, pas un élément de décor validé.

Les numéros de poste, heures, destinations et codes ci-dessous servent d'exemples ; ils seront adaptés au poste retenu.

| ID | Postes | Écart sur le mur est | Comment le joueur peut le vérifier | Statut |
| --- | --- | --- | --- | --- |
| E01 | 1–8 | L'en-tête du tableau indique un autre numéro de poste. | Comparer avec le grand panneau **POSTE DE TRI x/8** de la pièce. | Retenue |
| E02 | 1–8 | La ligne du code de destination du colis donne une autre ville sur le tableau. | Comparer le code et la ville imprimés sur le colis avec la ligne correspondante. | Retenue |
| E03 | 1–8 | Deux destinations différentes portent le même code dans la liste du tableau. | Les deux lignes du tableau se contredisent, sans connaissance extérieure. | Retenue |
| E04 | 1–7 | La flèche « poste suivant » du plan mural pointe vers l'ouest. | Comparer la flèche avec la porte est et les numéros des postes. | Retenue |
| E05 | 2–8 | Deux petites plaques magnétiques de destination ont échangé leurs emplacements sur le tableau. | Les codes gravés sous les plaques ne correspondent plus aux plaques posées dessus ; les postes précédents montrent leur disposition normale. | Retenue |
| E06 | 1–7 | La plaque au-dessus de la porte est indique un mauvais numéro de poste suivant, par exemple « VERS POSTE 4 » au poste 2. | Comparer la plaque avec le grand panneau du poste actuel : le passage suivant doit conduire au numéro immédiatement supérieur. | Retenue |
| E07 | 1–7 | Un seul panneau de la fenêtre latérale est devenu transparent. | Comparer avec les autres panneaux floutés du même poste. | Retenue |
| E08 | 1–8 | La limite de poids indiquée pour la route du colis a changé sur le tableau. | Le poids lu sur la balance correspond à celui du colis, mais dépasse la limite affichée pour sa route. | Retenue |
| E09 | 1–8 | La fiche du colis indique deux étapes successives dans le bon ordre, mais la seconde porte une heure antérieure à la première. | Les deux heures inscrites sur la même fiche racontent l'inverse de l'ordre des étapes. | Retenue |
| E10 | 1–8 | Le plan du mur est porte la version **TRI-04**, alors que l'ordinateur du bureau ou une note de service indique que la version en vigueur est **TRI-05**. | Comparer les numéros de version ; l'ancien plan est encore présenté comme actif. | Retenue |
| E11 | 1–8 | Une ligne du tableau indique « Lyon → quai B », tandis que le petit plan accolé indique « quai B → Lille » et « Lyon → quai C ». | Suivre la destination du colis dans la liste, puis vérifier le quai sur le plan du même mur. Le « quai » est un emplacement d'expédition du hangar. | Retenue |
| E12 | 1–8 | La fiche du colis sur le mur est affiche le code de tri **AB-74**, alors que le colis et l'ordinateur du bureau affichent **AB-47**. | Deux chiffres sont inversés sur la fiche du mur est ; les deux autres sources concordent. | Retenue |
| E13 | 1–8 | Le tableau marque le contrôle du poste actuel comme terminé alors que le joueur n'a pas encore appuyé sur un bouton. | Comparer l'état « terminé » avec le numéro du poste et l'état de la table avant décision. | Retenue |

L'état normal du mur est se déduit en retirant ces écarts : informations cohérentes, signalétique correcte et vitrage latéral flouté. Les plages figurent dans le [tableau de suivi](suivi-anomalies.md). Les indices doivent rester lisibles ; la difficulté vient de la comparaison à faire.
