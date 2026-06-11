# Sparengine — Missing Documents

Prototype d'un onglet **Missing Documents** pour la plateforme de gestion d'actifs aéronautiques **Sparengine**, conçu pendant un Design Sprint (Master Innovation, TBS Paris).

> **How Might We** — *Comment récupérer les documents manquants d'un avion, à partir des événements de sa propre histoire ?*

Dans un audit d'aviation privée (cession ou retour de lease), le dossier d'un avion est souvent incomplet : des documents manquent, dispersés entre opérateurs, ateliers et hangars. L'outil part de **chaque événement de maintenance** (la timeline de l'avion), déduit les documents qui auraient dû exister, repère ceux qui manquent, identifie **qui les détient** et permet de les **récolter** — demande email préremplie en un clic ou upload direct.

## Démo

Ouvrez simplement **`index.html`** dans un navigateur. Aucune dépendance, aucune installation : HTML / CSS / JavaScript natif, tout dans un seul fichier.

Si le dépôt est publié via **GitHub Pages**, la démo est accessible directement à l'URL du site.

## Fonctionnalités

- **Bandeau d'alerte AOG** — l'avion est signalé « cloué au sol » tant qu'un document critique manque ; l'alerte se lève dès qu'il est fourni.
- **Table des documents manquants** — priorité, événement lié, cause détectée, source probable, statut ; recherche, filtres et tri.
- **Cycle de récolte** — *À demander → Demande envoyée → Reçu*, avec upload qui réintègre le document au dossier.
- **Onglet Timeline** — vie de l'avion année par année, tri récent/ancien, filtre « documents manquants uniquement », et lien direct depuis un document vers son événement.
- **Onglet CRM** — base de contacts (CRM connecté + noms extraits des documents) ; le bouton *Request* ouvre le bon contact avec un email prérempli.
- **Assistant IA flottant** — analyse, source recommandée et preuves utilisées, sans encombrer la page.

## Stack

HTML5, CSS3, JavaScript vanilla. Zéro framework, zéro build.

## Structure

```
.
├── index.html      # le prototype complet
└── README.md
```

## Statut

Prototype de design sprint — données simulées (avion ATR72-212A · MSN 0001 · 9H-SLA). À des fins de démonstration.
