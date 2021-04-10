# Avurnavs

Swail a à coeur la sécurité en mer. Nous nous sommes donnés pour mission d'apporter des solutions numériques permettant d'augmenter la sécurité en mer.

Les AVURNAVs, Avis Urgents Aux Navigateurs, modifient quotidiennement les règles de navigation en mer dans les eaux territoriales françaises.

Données textuelles, peu ou pas formatées, notamment en ce qui concerne les coordonnées géographiques reportées, ainsi que les dates d'application des avis, les AVURNAVs demandent un traitement humain peu compatible avec les méthodes électroniques de navigation utilisées aujourd'hui.

Le temps nécessaire à leur report dans les dispositifs électroniques et le traitement humain propice à des erreurs de lecture induisent que peu de marins, notamment amateurs, ne les consultent et ne les reportent sur des cartes.

Nous avons construit une série d'expressions régulières pouvant être appliquées au texte des AVURNAVs pour une interprétation des données contenues, notamment les coordonnées géographiques et les dates.

A partir de ces données, nous avons construit une liste des ZONEX et les coordonnées géographiques, interprétable par une machine.

## Ressources

Les préfectures maritimes proposent un flux RSS des AVURNAVs:
- [Manche](https://www.premar-manche.gouv.fr/avis/rss/AVURNAV?format=rss)
- [Atlantique](https://www.premar-atlantique.gouv.fr/avis/rss/AVURNAV?format=rss)
- [Méditerranée](https://www.premar-mediterranee.gouv.fr/avis/rss/AVURNAV?format=rss)
