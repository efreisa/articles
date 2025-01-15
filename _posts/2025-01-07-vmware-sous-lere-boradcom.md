---
title: VMware sous l'Ère Broadcom - La Révolution des Tarifs qui Fait Grincer des Dents
date: 2025-01-07 16:33:00
categories: [Cloud]
tags: [conviction]
img_path: /assets/img/
image:
  path: vmware-alternatives.png
  alt: Deux chemins possibles, on-prem ou cloud
render_with_liquid: false
---

> **La politique tarifaire agressive de Broadcom pousse à tout repenser.**
>
> Les solution VMware sont fondamentalement le cœur d'un vaste écosystème qui constitue le socle du Système d'Information, ceci impose de s'adapter. Dans ses capacité à répondre rapidement et à fournir des solutions innovantes cloud devient une alternative intéressante.

# Context

La prise de contrôle de VMware par Broadcom a entraîné des changements dans les plans tarifaires. L'élévation de coût constaté étant 3 à 17 fois le prix initial. Le positionnement sur le marché et un resserrement des relations commerciales et de partenariat. Ces tendances concrètes soulèvent des risques qui doivent être atténués et anticipés avec une forte adhésion des clients.

La raison est que Broadcom a décidé de réduire drastiquement le catalogue d'offre tout en abandonnant le modèle à licences perpétuelles. Aujourd'hui, il n'existe plus plus que VMware vSphere Foundation (VVF) et VMware Cloud Foundation (VCF).

## VMware vSphere Foundation (VVF)

VMware vSphere Foundation est une solution conçue pour déployer et gérer une infrastructure IaaS contenue. Elle inclut les composants suivants[1](https://docs.vmware.com/en/VMware-vSphere-Foundation/index.html) :

- **VMware vSphere ESXi**
- **vCenter Server**
- **vSphere IaaS control plane**
- **VMware vSAN Enterprise** (100 GiB par cœur par hôte inclus)
- **VMware Aria Suite Standard** (incluant VMware Aria Operations, VMware Aria Operations for Logs, VMware Aria Suite Lifecycle, et VMware Aria Automation Orchestrator)

Des options supplémentaires peuvent être achetées pour améliorer l'environnement, telles que VMware Live Recovery, VMware Tanzu, et VMware NSX Advanced Load Balancer.

### VMware Cloud Foundation (VCF)

VMware Cloud Foundation est Software Designed Datacenter Solution[2](https://docs.vmware.com/en/VMware-Cloud-Foundation/5.2/vcf-getting-started/GUID-07411CF9-AD3F-43EA-A348-A89940C2D4A2.html). Elle inclut les composants suivants :

- **vSphere** (incluant ESXi et vCenter Server)
- **vSAN** (stockage agrégé local ou direct)
- **NSX** (réseau et sécurité)
- **vSphere with Tanzu** (gestion des conteneurs)
- **VMware Aria Suite** (gestion du cloud)

# Challenge

Dans ce contexte, de plus en plus d'entreprises cherchent à identifier des alternatives et à planifier des scénarios qui leur permettront de réduire les risques associés et de contrôler cette transformation, dans le but de minimiser l'impact sur leurs activités.

Au-delà d'un simple problème de virtualisation, les produits VMware sont essentiels à une large gamme de processus de maintenance des systèmes d'information, tels que l'orchestration, la sauvegarde et l'observabilité. Cette large gamme de fonctionnalités et leurs alternatives doivent être examinées en détail lors de l'identification des cibles viables.

Le sujet n'est donc pas simplement technologique mais est une vraie remise en question du système d'information. Le graphique ci-dessous montre comment les alternative et les solutions cloud peuvent définir deux chemins pour répondre au challenge.

![Matrice de solution VMware](vmware-migration-path.png)

## Alternative as-is

Avec un long historique de concurrence féroce largement relayée par les médias, Nutanix et généralement la alternative considérée comme sérieuse évoquée. Par ailleurs, a date, Nutanix ne fait pas payer l'hyperviseur ce qui est une garantie de pérennité.

Toutefois, que ce soit Nutanix, Hyper-V ou Proxmox, les impacts du changement sont généralement plus étendus que l'on ne pourrait l'imaginer et surtout les temps de mise en oeuvre sont relativement long. Il faut effectivement oublier la possibilité de réutiliser les serveurs existants. De même que l'écosystème de stockage, monitoring, sauvegarde, réseau, et autres processus permettant d'assurer le respect des différentes contraintes de services ou réglementaires vont nécessiter des travaux plus ou moins intenses.

Il faut compter au moins 3 mois pour la selection l'acquisition et l'installation des nouveaux serveurs. Et ce pour initier l'étape la plus importante de réinstallation des applications. En effet, il n'est généralement pas possible de reprendre les systèmes en l'état. L'implication des métiers devient indispensable pour assurer la coordination des indisponibilités ainsi que d'assurer des qualification techniques des nouveaux socles.

Dans ces condition, l'abandon de VMware prendra entre 1 et 3 ans en fonction du rythme et de l'ampleur des travaux relatifs aux applications ainsi que le décomissionnement des tous les systèmes. Délais d'autant plus longs que les équipes doivent également être formées sur les nouveaux systèmes.

## Alternative cloud

Dans ce contexte, le cloud avec ses temps d'installation accélérés peut être une solution plus efficace.
Pour accélérer encore la démarche pour les clients ayant des difficultés de négociations avec Broadcom, Microsoft et Google propose des solution VMware dans leur cloud qui permettent de migrer de manière simple les applications.

Google VMware Engine ou Azure VMware Solution sont des instances Software Defined Data Center (SDDC) permettant via VMware HCX de migrer très facilement les VMs concernées. Ces instances sont des _Cloud dans le Cloud_ qui permettent de migrer sans difficulté de compétences ou de rupture technologiques puisqu'il est question de migration de VMware vers VMware.

Ces solutions permettent un migration dite _lift and shift_ :

- _Lift_ pour la migration des ressources en l'état avec un impact faible
- _Shift_ en permettant dans un second temps d'innover pour exploiter les nouveaux socles proposés par le cloud

# Conclusion

La remise en question initié par la nouvelle politique tarifaire de VMware n'a pas de cible unique. Cela reste pour les entreprises l'occasion d'innover pour identifier un nouveau modèle de gestion avec des destinations très différentes :

1. Rester avec VMware tout en cherchant de nouveaux axes d'optimisation des coûts dans les contrats, l'organisation ou les choix d'architecture
2. Rester avec des datacenter en propre mais migrer vers une solution technologique alternative qui nécessitera des travaux d'adaptation
3. Aller dans le cloud et initier une démarche d'innovation pour en maîtriser les coûts ainsi qu'un nouvel équilibre budgétaire Investissements vs Fonctionnement

Majoritairement, Broadcom impose une transformation plus qu'une adaptation. L'avenir nous révélera ceux et celles qui auront trouver le meilleure chemin.
