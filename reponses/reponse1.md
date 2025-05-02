## 	Exercice 4: Appels de methodes

## Déclarations
Point p = new Point(1,2);
Rectangle r = new Rectangle(p,2,3);
Rectangle t = new SlantedRectangle(p,2,3);
SlantedRectangle s = new SlantedRectangle(p,2,3);

## Méthodes appelées
Rectangle.surface();
Rectangle.rotate();
Rectangle.contains(Point);
SlantedRectangle.surface(); si override sinon : 
Rectangle.surface();
SlantedRectangle.rotate(); si override sinon :
Rectangle.rotate();
SlantedRectangle.contains(Point); si override sinon :
Rectangle.contains();
## Remarques 
tous les appels compilent car les types déclarées possèdent les signatures des methodes utilisées.

 