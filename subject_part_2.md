# intro

Blender est un logiciel ce 3d open source. C'est sûrement le logiciel le plus utilisé, car il permet de globalement tout faire : de la création de pièces techniques, d'animations, de rendus photo réalistes... Ce logiciel est ultra complet, et a donc une quantité faramineuse d'onglet, d'outils, et de modifieurs parmi lesquels on se perd rapidement, d'autant plus que la communauté crée tous les jours de nouveaux plugins pour en repousser les limites, l'objectif n'est donc pas de vous apprendre à utiliser Blender, mais plutôt de vous montrer le champs des possibles ! Aujourd'hui en vous montrant comment animer une forme simple !

# exercice 1

Supprimez le cube, créez un plan, Alez dans édit mod->clique droit->merge vertices. Extrudez le point restant pour en faire un fil, puis appliquez-lui un skin à modifier. bravo vous avez la base de votre jambe

# exercice 2

subdivisez la jambe crée en 3, pour créer les articulations., et créez une armature depuis le skin modifier de la dernière étape.

# exercice 3

créez un cube, ça sera notre personnage, et dupliquez les jambes pour lui en mettre sur ses 4 faces parentez tous les objets 

# exercice 4

créez des empties au bout des jambes (parentez les aussi au reste) et des cercle autour d'eux transformez les cercles en demis cercles, ce sera nos repère pour la forme des mouvements de déplacement des jambes, ils doivent donc tous être rotate dans le sens de la marche 

# exercice 5
 
bloquez les empties pour qu'il ne puissent plus que bouger sur la forme des demis cercles 

# exercice 6 

insérez des Keyframes pour faire votre première animation, il peuvent être vus et modifié dans la Timeline en bas de la vue 3d

# exercice 7

ouvrez un graph editor, cliquez sur votre cube (du corps) i-> insert location and rotation
dans le graph editor pressez juste N
maintenant, créez un mouvement, et de petite rotation aléatoire pour le corps

# exercice 8

donnez des matériaux a vos éléments, faites vous Plaisir !

# exercice 9 

créez votre premier rendu d'animation 

# exercice bonus

Créez une sphère, et un plan au-dessus de lui, subdivisez le plan, mettez le en smooth shading, et lancez une simulation de tissu pour le plan, de façon a ce qu'il s'entoure autour de la sphère
