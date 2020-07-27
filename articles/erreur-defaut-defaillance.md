# Erreur, défaut et défaillance

Bug, erreur, anomalie, défaut, défaillance, imprévu, mauvais comportement, crash, freeze, feature… et j’en passe.  
Tous ces termes sont souvent utilisés comme des synonymes pour indiquer qu’un logiciel ne fonctionne pas comme on le souhaiterait sous certaines conditions.

Dans les faits, l’ISTQB définit 3 termes spécifiques qui ont des sens bien différents et qui font régulièrement l’objet de questions à l’examen.

Ces termes sont :  
##### erreur, défaut et défaillance.

**L'erreur est humaine** et est à l'origine des défauts.  
**Les défauts sont des imperfections dans le logiciel**. Ces défauts peuvent engendrer des défaillances mais ce n’est pas nécessaire.  
Les défaillances sont des événements au cours desquels le logiciel ne fait pas ce qu’il devrait. Pour simplifier, **les défaillances sont ce que nous appelons couramment Bug ou Anomalie**.

Cela revient à ce schéma :

!(/img/erreur.png)

Comme vous pouvez le remarquer, l’origine des défaillances sont des défauts dont l’origine est une erreur qui est forcément humaine. Néanmoins, **un défaut n’engendre pas forcément une défaillance !**


#### TOUS LES DÉFAUTS N’ENGENDRENT PAS NÉCESSAIREMENT DE DÉFAILLANCES


Ce point est particulièrement important. Afin de vous en convaincre je pourrais dire qu’une erreur sur une fonctionnalité peut être couverte par des sécurités implémentées sur d’autres fonctionnalités comme des vérifications, mais même si cela est vrai, cela n’est pas aussi parlant qu’une analogie. Je vais donc passer par ce moyen avec un exemple dans la construction :

1. Un architecte conçoit ma maison. Dans ce cadre il doit prévoir de faire des murs en parpaings. Ces derniers seront alors recouverts d’un parement décoratif en pierre.
2. **L’erreur survient lors de l’achat des matériaux**. Le constructeur achète des briques rouge pour les murs
3. On a donc un défaut, la maison a des briques rouges au lieu des parpaings.
4. Au final il n’y a par contre **aucune défaillance** pour le propriétaire, en effet les murs sont aussi solides et l’esthétique inchangée car le parement cache le défaut. En fait, la seule différence est une meilleure isolation avec les briques rouges.


<rm-test@inrae.fr>
