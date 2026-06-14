# Intercom-csm-lab
Exploration pratique d'Intercom (Fin AI, workflows, Help Center, reports, outbound) pour se préparer à un rôle de Customer Success Manager en SaaS.

Dans le cadre de ma préparation à des postes de Customer Success Manager / Customer Care en SaaS, j'ai créé mon propre compte Intercom pour explorer concrètement les outils utilisés au quotidien par une équipe CSM dans un environnement IA-first.

<img width="1272" height="798" alt="Image" src="https://github.com/user-attachments/assets/f21a2638-c2fc-44f7-b18a-d7f2c70879a2" />

Intercom positionne son produit autour d'un support "AI-first" : channels, agent IA (Fin), Knowledge, Reports et Outbound forment un écosystème intégré plutôt que des outils séparés.

## 1. Inbox unifiée

<img width="1271" height="808" alt="Image" src="https://github.com/user-attachments/assets/739f6d5f-46cb-4f7f-a484-4afeff565d4a" />

Toutes les conversations multi-canaux (Messenger, Email, WhatsApp, téléphone) arrivent dans une interface unique. C'est le point d'entrée qui permet à une équipe CSM de ne rien manquer quel que soit le canal utilisé par le client.

## 2. Fin AI Agent, les 3 piliers pour l'entraîner

Avant de configurer un workflow, j'ai exploré la logique d'entraînement de Fin, l'agent IA :

- **Content** : ce que Fin sait, alimenté par le Help Center, la documentation
- **Guidance** : comment Fin se comporte, ton de voix, règles métier
- **Escalations** : quand Fin passe la main à un agent humain

J'ai construit un workflow simple dans Fin Studio : message d'accueil → "Let Fin answer" → deux branches selon le resolution state (Confirmed Resolution / Escalated vers un agent humain).

**Ce que ça m'a appris** : quand on forme un agent humain, il aide un client à la fois. Quand on forme correctement Fin, cette connaissance s'applique immédiatement à des milliers de clients en parallèle, le rôle du CSM évolue vers la maintenance de cette base de connaissances.

## 3. Help Center

J'ai créé une collection et publié un article ("Comment contacter le support ?") qui alimente directement Fin, illustrant le lien direct entre documentation et performance de l'IA.

## 4. Reports, AI & Automation

<img width="1522" height="893" alt="Image" src="https://github.com/user-attachments/assets/a964ba75-3e60-406f-91d5-db07023b1fd7" />

<img width="1528" height="737" alt="Image" src="https://github.com/user-attachments/assets/3b93c86a-e291-4a45-8543-de7e87244702" />

Exploration des métriques clés pour mesurer la performance du support :

- **Deflection rate** et **Resolution rate** : la part des conversations prises en charge et résolues par Fin
- **Median time to close** (10m35s) : la vitesse de résolution
- **CSAT** : la satisfaction client
- **New conversations by channel** : la répartition du volume

Ces métriques permettent de savoir si Fin performe correctement ou si la base de connaissances a besoin d'être enrichie.

## 5. Outbound, Engagement proactif

<img width="1523" height="824" alt="Image" src="https://github.com/user-attachments/assets/0630c2d4-0147-4c39-bebd-b00f7f64468b" />

Exploration des messages sortants (chat, email, product tour) pour engager proactivement les utilisateurs, en complément du support réactif.

## 6. Product Tour, Onboarding

<img width="1214" height="728" alt="Image" src="https://github.com/user-attachments/assets/3570e486-85cc-4ae5-9645-50300473d89d" />

Création d'un parcours d'onboarding en 3 étapes (Welcome / Your Dashboard / Account settings) pour guider un nouvel utilisateur vers les fonctionnalités clés dès son arrivée sur le produit.

## Compétences démontrées

- Configuration d'un outil de support client multi-canal
- Compréhension de la logique IA-first appliquée au support client
- Création et structuration de contenu de Help Center
- Lecture et interprétation de KPIs de support client
- Conception d'un parcours d'onboarding utilisateur
  
---

## Auteure

**Mina OUAAZIZ** 

À la recherche de rôles de Customer Success Manager / Customer Care en SaaS, avec plusieurs années d'expérience dans l'accompagnement client en secteur médico-social et auprès d'entreprises du BTP.
