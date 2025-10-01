---
sidebar_position: 1
title: Accueil
---

# Documentation des modules Ignition

---

## Sommaire

* [À propos](#à-propos)
* [Modules disponibles](#modules-disponibles)
* [Commencer](#commencer)
  * [Installation rapide](#installation-rapide)
* [Guides et tutoriels](#guides-et-tutoriels)
* [FAQ](#faq)
* [Notes de version](#notes-de-version)
* [Support & Contact](#support-contact)

---

## À propos

Bienvenue sur la documentation officielle des modules Ignition développés par **OperaMetrix**.

OperaMetrix conçoit des modules pour Ignition (Gateway, Vision, Perspective, et composants backend) destinés à améliorer la supervision, la connectivité et l'analyse des installations industrielles.

Cette documentation couvre :

* l'installation et la configuration des modules ;
* des guides pas-à-pas et des tutoriaux ;
* la référence API pour développeurs ;
* les meilleures pratiques d'intégration et de sécurité.

---

## Modules disponibles

* **Octopush** — Notification SMS et appels via Octopush
* **Teltonika** — Notification SMS via un routeur Teltonika

> Pour voir la liste complète et la documentation détaillée d’un module, rendez-vous dans la section *Modules* (menu à gauche).

---

## Commencer

### Prérequis

* Ignition Gateway compatible (consultez la page de compatibilité de chaque module).
* Droits d’administration sur le Gateway pour l’installation de modules.
* Sauvegarde du Gateway avant installation en production.

### Installation rapide

1. Téléchargez le fichier du module (`.modl`) depuis la page de téléchargement d'OperaMetrix.
2. Dans l’Ignition Gateway : `Config → Modules → Install or Upgrade`.
3. Sélectionnez le fichier `.modl`, validez et redémarrez le service si demandé.
4. Allez dans la page de configuration du module (sous `Config → Modules`) pour entrer vos clés/licences et paramètres initiaux.

> Astuce : installez d’abord en environnement de test et validez les backups avant toute mise en production.

---

## Guides et tutoriels

Chaque tutoriel inclut des captures d’écran, extraits de configuration et étapes de dépannage.

---

## FAQ

**Q — Comment obtenir une license ?**
R — Les informations de licence se trouvent sur la page produit ou contactez l’équipe OperaMetrix via la section Support.

**Q — Où trouver les logs ?**
R — Les logs du module sont disponibles via le logging d’Ignition ; certains modules ajoutent un onglet ‘Diagnostics’ avec des journaux détaillés.

---

## Notes de version

Consultez la page **Notes de version** pour chaque module : compatibilités, corrections, nouvelles fonctionnalités et instructions de mise à jour.

---

## Support & Contact

* **Support technique** : [contact@operametrix.com](mailto:contact@operametrix.example)
* **Ventes / licences** : [contact@operametrix.com](mailto:contact@operametrix.example)

Pour les demandes urgentes, fournissez : version du Gateway, versions des modules, fichiers logs et description détaillée du comportement.

---

