# Weekly Claw - Résumé session du 13 mai 2026

## Résumé court

Session Weekly Claw sur Discord autour de Hermes, OpenClaw, modèles locaux, souveraineté des données et coûts des agents. La session a surtout servi de découverte comparative entre Hermes et OpenClaw avec une installation live de Hermes, puis une discussion large sur le local, LM Studio, Gemma 4, Qwen 3.6, Claude Code, OpenAI, OpenRouter et les limites des agents.

NemoClaw n'a pas été traité en profondeur et a été gardé pour une prochaine session.

## Participants et nouveaux profils

### Gwen
- Background audit, conseil, product management.
- A travaillé sur des apps mobiles pour expatriés puis a cofondé une startup SaaS B2B dans la relocation internationale.
- Utilise ChatGPT, Claude, Gemini et NotebookLM.
- Intérêt principal: comprendre les agents, l'agentique et la couche technique, pas seulement les enjeux business.
- Participe à des think tanks IA et veut mieux relier vision métier et compréhension technique.
- N'a pas encore installé OpenClaw, mais souhaite s'y remettre.
- Sujet récurrent pour elle: contrôle des données et dépendance aux outils.

### Alexandre / Kijoupa
- A créé une plateforme comptable.
- Déploie OpenClaw sur sa plateforme, encore au stade prototype.
- Focus comptabilité et développement informatique.
- Utilise Claude Code tous les jours, ChatGPT et Gemini.
- Aide des entreprises à intégrer le cloud et gérer leurs données.
- Équipe de 4 développeurs.
- Point clé: sécuriser les preuves / process avant déploiement plus large.

### Marcel
- Basé à Barcelone, français non natif.
- Intéressé par Hermes.
- Construit une application dans le domaine médical.
- A testé OpenClaw puis l'a désinstallé pour des raisons de sécurité après des comportements jugés risqués.
- Besoin principal: agentique mieux contrôlée et plus sécurisée.

### Patrick
- Graphiste, consultant communication, graphisme et identité visuelle.
- Utilise surtout Gemini, Adobe Firefly, Nano Banana et ChatGPT.
- Intéressé par OpenClaw mais ne l'a pas encore installé par crainte qu'un agent fasse des erreurs sur son ordinateur.
- Besoin principal: comprendre ce qu'OpenClaw peut faire concrètement pour un profil design/communication.

### Pezo
- Build des agents IA depuis plusieurs mois.
- A beaucoup utilisé OpenClaw puis est passé fortement sur Hermes depuis environ 2 mois.
- Trouve Hermes moins fragile et demandant moins d'entretien dans son usage.
- Objectif: faire tourner des agents avec modèles locaux.
- Très intéressé par Qwen 3.5 / 3.6 et les workflows locaux.
- A créé un setup où Claude Code délègue des tâches à Hermes via MCP pour réduire la consommation de tokens.
- Pousse l'idée de construire un wiki personnel / base de connaissances exploitable par agents, inspirée des idées de Karpathy.

### Philippe / pchartois
- Organise le meetup Generative AI à Genève.
- Prochain meetup annoncé: 18 juin, chez Found à Cornavin.
- Changement de lieu après frictions logistiques sur le networking dans l'ancien lieu.
- Salle chez Found potentiellement jusqu'à 90 personnes, mais plutôt limitée à 50 pour rester confortable.

### Oriane / Henri-Anne
- Présente au début, en extérieur avec AirPods, peu d'informations métier captées dans le transcript.

## Points clés de la session

### 1. Format Weekly Claw
- Session hebdomadaire détente pour suivre l'actualité IA, tester des outils et partager des découvertes.
- Les nouveaux participants se présentent rapidement: activité, usage IA, blocages, objectif.
- Objectif communautaire: créer des connexions business et techniques entre membres.

### 2. Hermes vs OpenClaw
- Hermes a été présenté comme très proche d'OpenClaw: agents, navigateur, terminal, fichiers, plateformes de messagerie, tâches planifiées et mémoire persistante.
- Point fort perçu de Hermes: mémoire persistante et hype actuelle, notamment forte consommation de tokens sur OpenRouter.
- Installation live: Hermes détecte OpenClaw et propose d'importer certains éléments.
- Installation plus touffue que prévu, avec bugs initiaux en local via LM Studio.
- Premières impressions de Cyril: Hermes ressemble beaucoup à OpenClaw, mais l'UX et le setup local semblent moins fluides.

### 3. Local LLM et LM Studio
- Test de Hermes avec LM Studio et Gemma 4.
- Problème initial avec le modèle 2B et la fenêtre de contexte demandée.
- Passage au modèle 4B pour réussir à obtenir un démarrage.
- Conclusion pratique: faire tourner des agents en local est possible, mais la latence et le besoin de contexte rendent l'expérience plus lourde.

### 4. OpenClaw dashboard et contrôle
- OpenClaw a été montré comme plus lisible côté dashboard: sessions, channels, instances, usage, crons, agents, skills, nodes, config.
- Point différenciant mis en avant: contrôle central clair, ajout de skills, visibilité sur l'usage.
- Hermes semble manquer d'un panneau de contrôle aussi complet dans l'expérience testée.

### 5. Données, cloud, local
- Discussion forte autour du contrôle des données.
- Claude Code / Anthropic est jugé efficace, mais implique dépendance cloud, modèle imposé et contrôle limité.
- OpenClaw permet de choisir le modèle, le provider, les canaux et potentiellement de passer en local.
- Le local coûte moins cher à long terme en tokens, mais nécessite une machine coûteuse ou adaptée.

### 6. Coûts et tokens
- Les agents consomment vite énormément de tokens car ils injectent beaucoup de contexte à chaque action.
- OpenAI à 20 dollars est présenté comme une option très rentable actuellement pour utiliser OpenClaw / agents avec une limite confortable.
- Les modèles locaux réduisent les coûts variables mais demandent du hardware.

### 7. Modèles locaux discutés
- Gemma 4: modèle local open source intéressant, peut tourner sur machine et même téléphone selon le format.
- Qwen 3.5 / Qwen 3.6: modèles open source très performants, mais demandant souvent beaucoup de RAM/VRAM selon quantisation.
- Eurya / Infomaniak: discussion sur l'intérêt et la limite d'une IA suisse basée sur modèles open source chinois, avec dépendance à un prestataire tiers.

### 8. Questions ouvertes
- Quel outil est vraiment meilleur entre Hermes et OpenClaw en usage long terme ?
- Peut-on rendre les agents locaux assez rapides pour un usage quotidien ?
- Où placer le curseur entre confort cloud, coût, sécurité et souveraineté ?
- Quelle place pour NemoClaw dans une logique entreprise sécurisée ?

## Décisions / suites

- NemoClaw est repoussé à une prochaine session.
- Continuer les Weekly Claw chaque semaine.
- Encourager les membres à présenter leurs propres usages et démos.
- Préparer un événement IRL plus gros, potentiellement fin mai / début juin.
- Explorer une salle côté IBAV / Pont-Rouge.
- Noter le meetup Generative AI de Philippe le 18 juin chez Found à Cornavin.
