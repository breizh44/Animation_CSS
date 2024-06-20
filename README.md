# Animation_CSS
exemples d'animations en CSS


## Les transitions
Pour créer une transition, on a besoin de plusieurs informations :
- une propriété CSS à modifier
- une valeur initiale pour la propriété  CSS
- uen valeur finale pour la propriété
- une durée
- un événement pour déclencher la transition

### Exemple : agrandir un bouton au survol
- ajout de la propriété **transition-property** à la div .btn en lui indiquant que la transition doit êtr appliquée à la propriété **transform**
- utilisation de la pseudo-classe **:hover** pour déclencher la transition sur le survol
- ajouter la propriété **transition-duration** pour définir la durée de la transition

### Déclenchement des transitions : les pseudoclasses
https://openclassrooms.com/fr/courses/5919246-creez-des-animations-css-modernes/6340914-declenchez-vos-transitions-avec-les-pseudoclasses
- **:hover** déclenché au survol de la souris
- **:active** activé au clic de l'utilisateur (liens et boutons)
- **:focus** déclenchéee lorsque l'élément reçoit le focus
- **:valid** déclenchée si la validation du contenu s'effectue correctement par rapport au type de donnée attendue
- **:invalid** correspond à un élément dont la validation du contenu ne s'effectue pas correctement par rapport au type de donnée attendue
- **not()** correspond à la négation. Elle prend un sélecteur en argument et permet de cibler les éléments qui ne sont pas représentés par cet argument
- **:checked** correspond aux input de type checkbox, option ou radio qui sont cochés
- **:enabled** un élément avec lequel on peut **interagir**
- **:disabled** correspond à un élément dont l'interaction a été bloquée

On compte plus de 50 pseudoclasses

Remarque : utilisation des sélecteurs imbriqués pas claire => à creuser ! (https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_nesting/Using_CSS_nesting)
https://www.codeur.com/tuto/css/selecteurs-css/
