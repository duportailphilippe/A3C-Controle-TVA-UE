# Politique de sécurité — Contrôle TVA UE — VIES

La sécurité de l’extension **Contrôle TVA UE — VIES** est prise au sérieux.

Cette page décrit la procédure recommandée pour signaler une vulnérabilité ou un comportement susceptible d’affecter la sécurité de l’extension ou de ses utilisateurs.

---

## 🔐 Signaler une vulnérabilité

Si vous identifiez :

- une vulnérabilité de sécurité ;
- une possibilité d’exécution de code non prévue ;
- une fuite potentielle de données ;
- un accès excessif à une page Web ;
- un comportement inattendu lié au presse-papiers ;
- une mauvaise isolation des données locales ;
- une faiblesse affectant les permissions de l’extension ;
- une vulnérabilité permettant de contourner une protection du navigateur ;

merci de **ne pas publier immédiatement les détails dans une Issue GitHub publique**.

Contactez prioritairement A3C de manière confidentielle.

### Contact sécurité

**A3C Expert Comptable — Dunkerque**

E-mail :

`philippe@duportail.fr`

Objet conseillé :

`SECURITE — Extension Contrôle TVA UE — VIES`

---

## 📋 Informations utiles à fournir

Lorsque cela est possible, indiquez :

- la version de l’extension concernée ;
- la version de Google Chrome ;
- le système d’exploitation utilisé ;
- la fonctionnalité concernée ;
- les étapes permettant de reproduire le problème ;
- le comportement attendu ;
- le comportement effectivement constaté ;
- les éventuels messages d’erreur ;
- toute capture d’écran utile.

N’adressez pas de données confidentielles de clients ou de tiers si elles ne sont pas nécessaires à la compréhension du problème.

Lorsque des données réelles sont indispensables pour reproduire l’anomalie, anonymisez-les autant que possible.

---

## 🧪 Vérification du signalement

Après réception d’un signalement suffisamment documenté, A3C pourra notamment :

1. vérifier la reproductibilité du problème ;
2. évaluer son impact ;
3. déterminer si une correction est nécessaire ;
4. préparer une nouvelle version de l’extension ;
5. compléter, le cas échéant, les tests de non-régression concernés.

---

## 🚨 Divulgation responsable

Nous demandons aux personnes découvrant une vulnérabilité de laisser un délai raisonnable permettant :

- son analyse ;
- son éventuelle correction ;
- la préparation d’une version sécurisée ;
- sa diffusion auprès des utilisateurs ;

avant toute divulgation publique détaillée.

Cette démarche vise uniquement à limiter le risque d’exploitation d’une vulnérabilité avant sa correction.

---

## 🔄 Versions prises en charge

La version activement prise en charge est principalement :

**la dernière version publiée officiellement par A3C.**

Elle est disponible ici :

https://github.com/duportailphilippe/A3C-Controle-TVA-UE/releases/latest

Les versions plus anciennes peuvent ne plus recevoir de correctifs de sécurité.

---

## 🧩 Principes de sécurité de l’extension

Le développement de Contrôle TVA UE — VIES repose notamment sur les principes suivants :

- utilisation de Manifest V3 ;
- absence de code JavaScript exécutable distant ;
- absence de bibliothèques publicitaires ;
- absence de télémétrie générale de navigation ;
- limitation des autorisations au périmètre nécessaire ;
- permissions sensibles facultatives lorsque cela est possible ;
- absence de contrôle VIES automatique sans action volontaire de l’utilisateur ;
- stockage local des données gérées par l’extension ;
- distinction entre erreurs techniques et résultats métier ;
- tests de non-régression avant diffusion des versions.

---

## ⚠️ Dépendances et services externes

L’extension utilise des services tiers ou publics, notamment VIES, EORI et différents registres officiels.

Une indisponibilité ou une vulnérabilité affectant directement l’un de ces services externes n’est pas nécessairement une vulnérabilité de l’extension.

Toutefois, un comportement de l’extension qui exploiterait de manière incorrecte ou non sécurisée une réponse provenant de ces services peut être signalé.

---

## 📦 Vérification de la source

Téléchargez l’extension uniquement depuis les canaux officiels indiqués par A3C.

La dernière version officielle est disponible via :

https://github.com/duportailphilippe/A3C-Controle-TVA-UE/releases/latest

A3C ne peut garantir l’intégrité d’une copie modifiée, recompilée ou redistribuée par un tiers.

---

## 📄 Documents associés

- [Politique de confidentialité](./PRIVACY.md)
- [Conditions d’utilisation](./TERMS.md)
- [README de l’extension](./README.md)

---

© A3C — Tous droits réservés.
