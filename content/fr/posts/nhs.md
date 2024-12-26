---
title: NHS - Test and trace
seo:
  slug: nhs
date: 2021-08-01
---

**NHS Digital – Plateforme nationale de dépistage COVID-19:**

[[toc]]

## Résumé

En tant qu’Architecte de solution pour le programme national de dépistage COVID-19 du NHS, j’ai dirigé la conception et la mise en œuvre d’une plateforme digitale à grande échelle, permettant aux citoyens de réserver un test, enregistrer leur kit, et recevoir leurs résultats. En parallèle, nous avons développé une couche d’intégration pour les données de pilotage (MI) afin de fournir des tableaux de bord décisionnels et des rapports en temps réel aux autorités sanitaires.

<!-- {% image "/assets/img/rbs.jpg", "RBS 6 Nations iPhone application", "100vw", "RBS 6 Nations iPhone application", "square", "lazy", "auto", "async", "2400", "1600" %} -->

---

## Problème

Face à l’urgence de la crise sanitaire, le gouvernement britannique devait mettre en place une infrastructure numérique fiable et complète pour gérer le dépistage massif de la population.

La plateforme devait prendre en charge des millions d’enregistrements et de réservations par semaine, assurer la traçabilité des échantillons, et garantir la transmission sécurisée des résultats aux usagers, aux autorités locales et aux médecins généralistes.

Les systèmes existants n’étaient ni conçus ni dimensionnés pour répondre à une telle complexité ni à ce niveau d’exigence opérationnelle.

---

## Solution

J’ai conçu une architecture sécurisée, événementielle et cloud-native sur AWS, capable de supporter une montée en charge rapide et une interconnexion fluide entre les différents acteurs. Les principales réalisations incluent :

- Digitalisation complète des parcours de test en centre, incluant la réservation, l’enregistrement, le suivi des kits et la validation des échantillons.

- Développement d’une plateforme de pilotage (MI), fournissant des tableaux de bord en quasi temps réel pour le suivi opérationnel et stratégique.

- Conception des flux de données bout-en-bout, garantissant l’envoi rapide et fiable des résultats vers les autorités locales, les dossiers médicaux des patients (GP) et les usagers.

- Scalabilité prouvée, permettant de gérer plus de 203 millions de tests, avec un objectif de 100 000 tests par jour atteint en moins de deux mois.

- 60 déploiements de code par mois, grâce à des pipelines CI/CD automatisés et une gouvernance des incidents.

- 485 millions de visites sur la plateforme, avec un pic journalier de 3 millions de visites sans interruption critique de service.

## Résultat

La plateforme est devenue l’épine dorsale digitale du programme national de dépistage au Royaume-Uni.

Elle a permis de répondre aux enjeux de masse, d’assurer la fluidité des opérations, de renforcer la confiance des citoyens, et d’offrir aux autorités sanitaires les outils de suivi et d’aide à la décision indispensables dans un contexte d’urgence.

---