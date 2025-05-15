# LearningPragmaticProgrammer
Notes about my first lecture of The Pragmatic Programmer: From Journeyman to Master book

***
## Chapitre 2 : une approche pragmatique
- Noter dans son "carnet de bord d'ingénieur" les choix qui s'offrent à soi
- laisser une étiquette dans le code source

Plus tard, lorsque le code devra être modifié, on pourra regarder en arrière et avoir un retour d'information.<br/>
Cela pourra m'aider la prochaine fois que je suis confronté à une situation similaire

### Balles traçantes
In new projects your users requirements may be vague. Use of new algorithms, techniques, languages, or libraries unknowns will come. And environment will change over time before you are done. We're looking for something that gets us from a requirement to some aspect of the final system quickly, visibly, and repeatably.

Tip 20: Use Tracer Bullets to Find the Target

Advantages:
- Users get to see something working early
- Developers build a structure to work in
- You have an integration platform
- You have something to demonstrate
- You have a better feel for progress

Principe : rechercher les exigences les plus importantes, celles qui définissent le système, et les implémenter (à travers toutes les couches), sans implémenter le reste. Montrer le résultat à l'utilisateur et bien lui communiquer que ce qu'il voit n'est pas "mûr", pas fini.


**Code That Glows in the Dark**

    Tracer bullets operate in same environment with same constraints as real bullets.

    Immediate feedback to the gunner.

    To get similar effect in code, we look for something that gets us from requirement to some aspect of final system quickly, visibly, and repeatably.

    How to do this in code?
        Look for important requirements of the system - the Must Haves to start with
        Look for the grey areas which has the huge risk of implementation

    Then, prioritize your development so that these are the first areas you code.

    Use Tracer Bullets to Find the Target

    The very first tracer bullet is Hello World
    Then built the skeleton of the system which is needed

**An example**

**Architectural Layers**

    Above system has five architectural layers.
    To understand how we can integrate them, we do a simple feature that uses all the layers.
    The diagonal line shows the path that feature takes through the code.
    To make the feature work, we need to just implement the solidly shaded areas in the diagram and the stuff with the squiggles will be done later.

### Protype
**Définition et élements :**
<br/>Un prototype est un code jetable, fait pour tester une idée, ou pour montrer quelque chose sans toute la machinerie derrière (par ex : une maquette graphique).
<br/>Tout ce qui appartient à ce que veut tester le prototype (et nous-mêmes !) est suffisamment élaborer pour **MONTRER** et/ou **EXPERIMENTER**.
<br/>Tout ce qui est annexe, secondaire, mais parfois nécessaire est correct juste ce qu'il faut pour l'objectif précédent.
<br/>Ex : une nouvelle fois, une maquette avec un ou des résumés de ... films disons, mais le résumé contient le texte que nous connaissons bien : le lorem ipsum !

Par opposition au protoypage, si on a besoin de détails auxquels on ne peut renoncer, un syle de devb type "balles traçantes" est plus approprié.

**Quels éléments prototyper ?**
<br/>On peut créer des protoytpes pour :
- tester/expérimenter une architecture
- une nouvelle fonctionnalité dans un système existant
- la structure et le contenu des données externes
- les outils ou composants tiers
- ...

**Conclusion**
<br/>Le prototypage est un expérience d'apprentissage. Sa valeur ne réside pas dans le code produit, mais dans les leçons apprise. C'est là tout l'intérêt du prototypage.
<br/>*Note de moi-même : ne serait-ce point l'idée du **kata** ?*
  



<br/><br/>Content from The Pragmatic Programmer, by Andrew Hunt and David Thomas. Visit www.pragmaticprogrammer.com. Copyright 2000 by Addison Wesley Longman, Inc.
