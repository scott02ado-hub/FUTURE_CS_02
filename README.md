# Phishing Email Analysis Project

## 🎯 Objectif

Ce projet a pour objectif d’analyser plusieurs emails suspects dans un cadre éducatif afin de comprendre les techniques utilisées dans les attaques de phishing.

L’étude se concentre sur l’identification des indicateurs de compromission (IOC) tels que :
- Usurpation d’identité (spoofing)
- Échecs SPF / DMARC
- Liens malveillants
- Pièces jointes suspectes
- Scripts de redirection JavaScript
- Techniques d’urgence et d’ingénierie sociale

---

## 🛠️ Outils utilisés

- Google Header Analyzer
- MXToolbox (SPF / DKIM / DMARC checks)
- Inspection du navigateur (DevTools)
- Analyse manuelle des headers email
- Jeux de données GitHub sur le phishing

---

## 📧 Emails analysés

### Email 1 — Fake Fax Notification
- Échec SPF
- Échec DMARC
- Domaine usurpé (service de fax frauduleux type “MetroFax”)
- Lien malveillant
- Message basé sur l’urgence

**Risque : HIGH**

---

### Email 2 — Fake Voice Message
- Redirection JavaScript suspecte
- Spoofing de l’expéditeur
- Pièce jointe douteuse
- Domaine externe non fiable
- Texte obfusqué pour éviter la détection

**Risque : HIGH**

---

## 🔍 Indicateurs de compromission détectés

- Email spoofing
- SPF failure
- DMARC failure
- Liens malveillants (phishing URLs)
- Redirections JavaScript
- Pièces jointes suspectes
- Ingénierie sociale (urgence / pression)

---

## 📊 Résultats de l’analyse

Après inspection, les emails analysés ont été classés comme :

- ⚠️ Suspicious
- ❌ Phishing confirmé

Les messages montrent des techniques classiques utilisées dans les campagnes de phishing modernes.

---

## 🛡️ Recommandations de sécurité

Pour réduire les risques de phishing :

- Activer l’authentification multi-facteurs (MFA)
- Mettre en place des filtres anti-spam avancés
- Configurer correctement SPF / DKIM / DMARC
- Former les utilisateurs à reconnaître les emails suspects
- Ne jamais cliquer sur des liens ou pièces jointes non vérifiés

---

## 📌 Conclusion

Cette analyse met en évidence la sophistication croissante des attaques de phishing et l’importance des mécanismes de protection côté utilisateur et côté infrastructure.

La vigilance et les bonnes pratiques de cybersécurité restent essentielles pour réduire les risques de compromission.

---
