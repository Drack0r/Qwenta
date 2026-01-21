# Méthodologie de veille technologique

## Outils de veilles choisis

- ### daily.dev :

  Extension de navigateur + une interface web qui propose chaque jour une sélection de ressources en lien avec le développement logiciel, notamment le front-end (JS, CSS, frameworks, outils, tendances, etc.).

  <u>Justification :</u>
  - Agrégateur automatisé qui filtre et classe les articles par pertinence et popularité.
  - Permet un accès rapide aux tendances actuelles du développement web sans perdre de temps à chercher sur de multiple sites.
  - Interface personnalisable selon les technologies du projet.

- ### newsletter :

  _This Week In React_, _Frontend Weekly_, _Frontend Focus_, _tldr.tech_, _bytes.dev_

  <u>Justification :</u>
  - Sources curées par des experts reconnus de l'industrie, garantissant une qualité et une pertinence élevées.
  - Format digeste qui synthétise l'essentiel de l'actualité tech en quelques minutes de lecture.
  - Couvrent à la fois les aspects techniques spécifiques et les tendances générales du web.

- ### Notion :

  Application de productivité tout-en-un, elle permet de prendre des notes, organiser des projets, gérer des bases de données, planifier des tâches et centraliser des informations dans un seul espace.

  <u>Justification :</u>
  - Centralisation de toute la veille dans un seul outil.
  - Permet de créer une base de données structurée des articles avec tags, catégories et notes personnelles.
  - Facilite le partage et la collaboration avec l'équipe, et l'intégration directe dans les spécifications techniques.

## Axe 1 - Spécifique au projet Menu Maker

### Sources sélectionnées

- [React Official Blog](https://react.dev/blog) - Documentation officielle et annonces
- [CSS-Tricks](https://css-tricks.com) - Techniques de mise en page avancées
- [Smashing Magazine](https://www.smashingmagazine.com) - Design et UX
- [Headless CMS comparisons](https://jamstack.org/headless-cms/) - Choix CMS
- [MongoDB Blog](https://www.mongodb.com/developer/) - Base de données NoSQL
- [PostgreSQL About](https://www.postgresql.org/about/) - Base de données SQL
- [Vercel Blog](https://vercel.com/blog) - Déploiement et performance
- [Next.js Blog](https://nextjs.org/blog) - Framework React avancé

### Justification

Ces sources couvrent spécifiquement les technologies envisagées pour Menu Maker :

- **React/Next.js** : Framework principal pour l'interface utilisateur dynamique de création de menus
- **CSS-Tricks & Smashing Magazine** : Essentiels pour les défis de mise en page responsive et l'expérience utilisateur
- **Headless CMS** : Comparaisons nécessaires pour choisir la solution de gestion de contenu la plus adaptée aux besoins des utilisateurs
- **MongoDB vs PostgreSQL** : Décision critique entre NoSQL et SQL selon les besoins du projet
- **Vercel** : Solution de déploiement performante pour garantir la rapidité d'affichage des menus clients

### Impact sur les choix techniques

Cette veille permet de :

- **Justifier le choix React/Next.js** grâce aux dernières évolutions et bonnes pratiques
- **Sélectionner la base de données optimale** en comparant les performances SQL vs NoSQL
- **Choisir le CMS le plus adapté** aux besoins non-techniques des utilisateurs
- **Garantir des performances optimales** avec les dernières techniques de déploiement et optimisation
- **Assurer une UX moderne** avec les tendances actuelles en design web

## Axe 2 - Développement Web général

### Sources sélectionnées

- [MDN Web Docs](https://developer.mozilla.org/) - Standards web
- [Web.dev](https://web.dev/?hl=fr) - Bonnes pratiques Google
- [A List Apart](https://alistapart.com) - Accessibilité et standards
- [OWASP](https://owasp.org/) - Sécurité web
- [Can I Use](https://caniuse.com) - Compatibilité navigateurs
- [GitHub Blog](https://github.blog/category/engineering/) - DevOps et collaboration
- [Stack Overflow Blog](https://stackoverflow.blog) - Communauté développeurs

### Justification

Ces sources garantissent le respect des standards modernes du développement web :

- **MDN & Web.dev** : Références officielles pour les standards W3C et les recommandations Google
- **A List Apart** : Expertise reconnue en accessibilité web, cruciale pour toucher tous les utilisateurs
- **OWASP** : Sécurité indispensable pour protéger les données des utilisateurs et de leurs clients
- **Can I Use & State of JS** : Veille sur la compatibilité navigateurs et l'évolution de l'écosystème JavaScript
- **GitHub & Stack Overflow** : Pratiques DevOps et résolution de problèmes techniques courants

### Bénéfices pour le projet

Cette veille apporte :

- **Conformité aux standards** : Respect des bonnes pratiques d'accessibilité et de performance web
- **Sécurité renforcée** : Application des dernières recommandations OWASP pour protéger les données sensibles
- **Compatibilité élargie** : Support optimal sur tous les navigateurs utilisés
- **Qualité de code** : Adoption des meilleures pratiques de développement et de collaboration
- **Évolutivité** : Anticipation des tendances technologiques pour garantir la pérennité du projet

## Axe 3 – Tendances des librairies JavaScript

### Sources sélectionnées

- [State of JS](https://stateofjs.com) – Étude annuelle de référence sur l’écosystème JavaScript
- [Best of JS](https://bestofjs.org/) – Classement dynamique des librairies JavaScript populaires
- [npm trends](https://npmtrends.com/) – Analyse comparative des téléchargements npm
- [Github (Trending & Stars)](https://github.com/trending) – Indicateur de traction communautaire
- [JavaScript Weekly](https://javascriptweekly.com/) – Newsletter spécialisée JavaScript

### Justification

Ces sources permettent d’assurer une veille fiable et objective sur les **tendances des librairies JavaScript**, en distinguant clairement la **popularité médiatique** de l’**adoption réelle en production**.

- **State of JS** apporte une vision long terme basée sur des données quantitatives (taux d’adoption, satisfaction, intention de réutilisation), essentielle pour identifier les technologies pérennes.
- **Best of JS** met en évidence les librairies émergentes et leur dynamique de croissance, permettant de détecter rapidement les nouvelles tendances.
- **npm trends** fournit une mesure concrète de l’usage réel via les volumes de téléchargements, critère clé pour évaluer la maturité d’une librairie.
- **GitHub (Trending & activité)** permet d’analyser la vitalité d’un projet (maintenance, issues, contributions), ainsi que son adoption par la communauté open source.
- **JavaScript Weekly** complète cette veille par une curation humaine, filtrant les annonces réellement significatives de l’écosystème.

### Impact sur les choix techniques

Cette veille permet de :

- **Éviter les effets de mode** en s’appuyant sur des indicateurs d’adoption réels
- **Sélectionner des librairies matures et maintenues**, adaptées à un projet professionnel
- **Anticiper les évolutions de l’écosystème JavaScript** sans remettre en cause l’architecture existante
- **Justifier les choix technologiques** auprès d’une équipe
- **Garantir la pérennité et la maintenabilité du projet** sur le long terme
