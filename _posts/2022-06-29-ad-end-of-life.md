---
title: L'AD aux orties
description: "Quel alternative à cet indispensable qui accompagne les DSI depuis le début du 21eme siècle."
date: 2022-06-29 10:00:00
categories: [Opinion]
---

L'AD s'est imposé dans le début des années 2000. Il est devenu aujourd'hui un frein à l'évolution vers le Cloud.
Trop _on-prem_ et orienté serveur, il souffre d'un attachement à des contraintes techniques d'un autre temps.

# Fin des VMs

A l'adoption des services PaaS et SaaS, le IaaS est à la peine. Cela pour trois raisons simples : temps de maintenance,
coûts (hébergement, licences, maintenance) et automatisation.

Le temps de maintenance qui impose des redémarrages réguliers pour appliquer des correctifs ou évolution fait qu'il est
Indispensable de gérer plusieurs vm pour porter un AD. Chacune devant être monitoré pour assurer la continuité. Ceci
occasionne des ruptures de services qui peuvent avoir des effets de bords.

Les coûts sont plus importants puisqu'il est nécessaire de créer des environnements réseau dédiés non exposés sur internet,
de même qu'il est nécessaire d'acquérir des licences, de les renouveler. Tout ceci nécessite des maintenances et de la
gestion, soit des couts additionnels qui sont inclus dans les solutions PaaS ou SaaS.

Enfin un vm est un écosystème complexe contenant un matériel (virtuel), un système d'exploitation et des applications.
Ceci rend l'automatisation plus complexe, d'autant que les considérations de consolidation vont faire que l'on ne va
généralement pas mettre une unique fonction sur une vm. Par ailleurs, il faut créer les réseaux qui interconnecte les VMs
et enfin il faut assurer la redondance des applications.

A suivre...
