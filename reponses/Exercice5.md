## Exercice 5

## Elements de reponses
la classe Dessin telle qu'elle est actuellement ne peut pas contenir des rectangles inclinés. Elle utilise un tableau de Rectangle, qui fait réference à des rectangles classiques alignés avec les axes(comme ceux de java.awt.Rectangle), sans rotation.

## Modification fonctionnelle
 la methode surface fonctionnerait mieux pour le cas des rectangles non inclinés. En cas d'inclinaison, le calcul de surface dependrait de la géometrie reelle de l'objet ce qui necessiterait un traitement different.
 
 la méthode contains serait fondée sur un test simple de position x/y et ne fonctionnerait plus correctement si les rectangles etaient inclinés.
 
 la méthode hull devrait egalement etre repensée pour des rectangles inclinées elle necessiterait une approche géometrique plus avancée pour prendre en compte les sommets réels de chaque rectangle.
