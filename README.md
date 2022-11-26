# TP02
## Etude de cas : Modélisation des concepts d'examen, question et réponse
Un examen contient des questions, à chaque question est attribué un nombre de points dans le contexte de celui-ci.

Un examen a un intitulé et une durée et peut être ouvert et refermé dans un intervalle supérieur ou égale à la durée de celui-ci.

Il existe deux catégories de questions: les questions ouvertes et les questions à choix multiples.

Parmi les choix proposés, une question à choix multiple peut admettre aucune, une ou plusieurs bonne réponses (voire toutes).

Une question dichotomique est une question fermée accompagnée par deux possibilités de réponse seulement. Ces réponses expriment en général des oppositions de type “oui / non” ou "vrai/faux".

La note attribuée pour une réponse dépend la complétude de celle-ci, il peut être attribué une pénalité (retrait de points) aux mauvaises réponses.

Pour les QCM il est possible de demander le degré de certitude (peu sûr, moyennement sûr, tout à fait sûr) pour chacune des réponses, cette information métacognitive peut être utilisée pour pondérer la note attribuée à une réponse selon une formule de calcule.

La prestation d'un candidat qui a passé un examen est composée de l'ensemble des réponses aux questions constituant celui-ci.


![image](https://user-images.githubusercontent.com/116631139/204088830-106ea9f3-491c-4e88-a834-9d4dfaa4e34b.png)
