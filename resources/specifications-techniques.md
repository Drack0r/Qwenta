# Spécifications techniques

**[Nom du projet + nom du client]**

---

## Informations générales

| Élément         | Valeur                                            |
| --------------- | ------------------------------------------------- |
| **Version**     | 1.0                                               |
| **Auteur**      | [nom de l’auteur]                                 |
| **Date**        | [date de réalisation du document]                 |
| **Approbation** | [nom de la personne qui doit valider le document] |

---

## Sommaire

1. [Choix technologiques](#i-choix-technologiques)
2. [Liens avec le back-end](#ii-liens-avec-le-back-end)
3. [Préconisations concernant le domaine et l’hébergement](#iii-préconisations-concernant-le-domaine-et-lhébergement)
4. [Accessibilité](#iv-accessibilité)
5. [Recommandations en termes de sécurité](#v-recommandations-en-termes-de-sécurité)
6. [Maintenance du site et futures mises à jour](#vi-maintenance-du-site-et-futures-mises-à-jour)

---

## I. Choix technologiques

### État des lieux des besoins fonctionnels et de leurs solutions techniques

| Besoin                                 | Contraintes                                                                                                       | Solution            | Description de la solution                                                                                       | Justification                                                        |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | ------------------- | ---------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| Ex. : Création d'une catégorie de menu | Ex. : L'ajout d'une catégorie doit pouvoir se faire directement sur l'écran de création de menu depuis une modale | Ex. : `react-modal` | Cette librairie React permet de créer simplement des modales performantes et accessibles avec un minimum de code | 1. Cohérente avec un projet React<br>2. Librairie largement utilisée |

---

## II. Liens avec le back-end

- **Langage serveur** :  
  Ex. : Node.js / PHP / Python / etc.

- **API** :  
  Une API est-elle nécessaire ?

  - Oui / Non
  - Si oui, laquelle ?

- **Base de données** :  
  Ex. : SQL / NoSQL

---

## III. Préconisations concernant le domaine et l’hébergement

- **Nom de domaine** :  
  Ex. : `mon-site.fr`

- **Hébergement** :  
  Ex. : OVH / Vercel / Netlify / AWS

- **Adresses e-mail** :  
  Ex. : `contact@mon-site.fr`

---

## IV. Accessibilité

- **Compatibilité navigateurs** :  
  Chrome, Safari et Firefox

- **Types d’appareils** :
  - Desktop

---

## V. Recommandations en termes de sécurité

- Gestion des accès aux comptes
- Sécurisation des plugins / dépendances
- Bonnes pratiques générales (mots de passe, HTTPS, etc.)

---

## VI. Maintenance du site et futures mises à jour

- Grandes lignes du contrat de maintenance :
  - Mises à jour techniques
  - Correctifs de sécurité
  - Évolutions fonctionnelles
