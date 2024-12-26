---
title: Transformation digitale des services d'immigration
seo:
  slug: home-office
date: 2023-01-01
---

**Transformation digitale des services d'immigration:**

[[toc]]

## Résumé

La bureau du Home Office britannique gère les demandes de visa en ligne pour les personnes souhaitant entrer ou rester au Royaume-Uni.

Une étape essentielle de ce processus est le paiement de la « Immigration Health Charge » (IHS), une redevance obligatoire.

En tant que Technical Lead et Architecte de solution, j’ai dirigé la conception et la mise en œuvre d’une nouvelle couche d’intégration pour prendre en charge le calcul, le paiement et l’accès aux informations IHS, tout en garantissant performance, conformité et résilience à l’échelle nationale.

<!-- {% image "/assets/img/rbs.jpg", "RBS 6 Nations iPhone application", "100vw", "RBS 6 Nations iPhone application", "square", "lazy", "auto", "async", "2400", "1600" %} -->

---

## Problème

Le système hérité, géré par un prestataire tiers, était fragmenté, peu fiable et entraînait des erreurs de paiement ainsi que des retards pour les demandeurs.

De plus, les agents du Home Office manquaient de visibilité en temps réel pour suivre le statut des redevances, ce qui complexifiait le traitement des dossiers.

La migration prévue depuis l’ancien système représentait un risque important en termes de continuité de service et d’intégrité des données.

---

## Solution

J’ai conçu une architecture de microservices sécurisée et événementielle sur AWS (Kubernetes, Java, TypeScript), intégrée aux systèmes internes du Home Office et à divers services tiers.

L’un des enjeux majeurs fut la migration complète des données actives de l’ancien système vers la nouvelle plateforme développée.

J’ai concu, develope et piloté cette migration de bout en bout, en définissant une stratégie robuste avec validation automatique, traçabilité des données, et mécanismes de retour arrière.

Nous avons mis en place des pipelines CI/CD, une infrastructure-as-code et des outils de supervision pour garantir la stabilité et la fiabilité du service.

## Résultat

Transition réussie vers une plateforme moderne, sans interruption de service.

Le système traite désormais plusieurs milliers de demandes par jour avec un traitement plus rapide, une meilleure visibilité pour les agents, et une fiabilité renforcée des données sur l’ensemble du parcours IHS.



---