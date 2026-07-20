# 🔒 Politique de Confidentialité — KebabBot

**Dernière mise à jour** : 20 juillet 2026
**Version** : 1.0
**Responsable du traitement** : DealerDeKebab
**Base légale** : Article 6.1.f du RGPD (intérêt légitime)

---

## 📋 Introduction

Cette **Politique de Confidentialité** explique quelles données personnelles sont collectées par **KebabBot** ("le Bot"), pourquoi elles sont collectées, comment elles sont utilisées, et quels sont tes droits en tant qu'utilisateur.

**KebabBot est conforme au RGPD** (Règlement Général sur la Protection des Données) — Règlement UE 2016/679.

---

## 1. 📊 Données collectées

### 🤖 Collectées automatiquement

Lorsque tu utilises le Bot sur un serveur Discord, les données suivantes sont collectées automatiquement :

| Donnée | Description | Finalité |
|--------|-------------|----------|
| 🆔 **Discord ID** | Ton identifiant Discord unique | Identification |
| 🏰 **Guild ID** | ID du serveur Discord | Configuration par serveur |
| ⏱️ **Temps vocal** | Minutes passées en vocal | Statistiques + XP |
| 💬 **Nombre de messages** | Compteur de messages envoyés | Système XP |
| 🎮 **Jeux joués** | Nom des jeux détectés via Discord Rich Presence | Game Tracker + stats |
| 🕐 **Timestamps** | Dates d'activité (join/leave vocaux) | Statistiques |
| 🏆 **XP + Niveau** | Progression sur le serveur | Système de niveaux |
| 💰 **Coins** | Économie virtuelle du bot | Système économique |

### ✋ Collectées volontairement

Ces données ne sont collectées que si **tu les fournis explicitement** via une commande :

| Donnée | Commande | Finalité |
|--------|----------|----------|
| 🎂 **Date d'anniversaire** | `/birthday set` | Souhaits d'anniversaire |
| 🎮 **Profils gaming** | `/rl link`, `/lol link`, `/val link`, `/cs2 link` | Trackers stats |
| 🎯 **Rôles auto-attribués** | Selfroles panels | Personnalisation |
| 🎯 **Profil LFG** | `/lfg profile` | Matchmaking |
| 📝 **Bio + Liens** | `/profile bio`, `/profile links` | Personnalisation |
| 🔔 **Abonnements notifs** | `/gameping enable` | Notifications jeux |

---

## 2. ❌ Ce que KebabBot NE collecte PAS

Nous ne collectons **jamais** :

- ❌ Le **contenu de tes messages** (jamais stocké ni analysé)
- ❌ Les **contenus vocaux** (jamais enregistrés)
- ❌ Les **fichiers/images** que tu envoies (jamais analysés)
- ❌ Les **messages privés** (aucun accès aux DMs entre utilisateurs)
- ❌ Les **données de paiement** (le Bot est 100% gratuit)
- ❌ Ton **email**, adresse IP ou données personnelles hors Discord
- ❌ Les **conversations vocales** (jamais transcrites)

**Note importante sur l'AutoMod** : Bien que le Bot analyse les messages en temps réel pour détecter spam/phishing (via l'intent Message Content), **aucun message n'est stocké** en base de données à cette fin.

---

## 3. 🎯 Finalités du traitement

Tes données sont utilisées uniquement pour :

- 🏆 Générer les **leaderboards** et classements
- 📈 Calculer ton **niveau XP** et progression
- 🎨 Afficher tes **statistiques gaming** (canvas premium)
- 🎂 T'envoyer un **message d'anniversaire** annuel
- 🎯 Personnaliser ton **expérience** sur le Bot
- 🎮 Détecter tes **jeux préférés** pour les stats
- 🛡️ Assurer la **sécurité** (anti-abus, anti-raid)
- 📊 Améliorer le Bot en fonction des **usages**

---

## 4. 🌍 Hébergement des données

### 🇫🇷 Localisation

- **Serveur** : OVH (Roubaix, France 🇫🇷)
- **Base de données** : PostgreSQL 17 (locale)
- **Sauvegardes** : Locales chiffrées

### 🔒 Sécurité

- ✅ **HTTPS/SSL** pour toutes les communications
- ✅ **Isolation** des données par serveur Discord
- ✅ **Accès restreint** au seul créateur
- ✅ **RGPD compliant** (hébergement UE, aucun transfert hors UE)
- ✅ **Sauvegardes régulières** pour éviter la perte de données

### 📅 Durée de conservation

- Les données sont conservées **tant que le Bot est utilisé** sur ton serveur
- Suppression **immédiate** sur demande via `/data delete`
- **Nettoyage automatique** des données inactives après **12 mois** d'inactivité

---

## 5. 🗑️ Tes droits (RGPD)

Conformément au RGPD, tu disposes des droits suivants :

### 👁️ Droit d'accès (Article 15)

Tu peux voir **toutes tes données stockées** via :
```
/data view
```

### 📥 Droit à la portabilité (Article 20)

Tu peux exporter tes données en **format JSON** via :
```
/data export
```

Le fichier téléchargeable contient l'intégralité de tes données.

### 🗑️ Droit à l'oubli (Article 17)

Tu peux **supprimer définitivement** toutes tes données via :
```
/data delete
```

**⚠️ Attention** : Cette action est **irréversible**. Tes profils, XP, historique gaming, etc. seront supprimés à jamais.

### ✏️ Droit de rectification (Article 16)

Tu peux modifier certaines données (bio, liens, birthday) via les commandes correspondantes.

### ✋ Droit d'opposition (Article 21)

Tu peux **cesser d'utiliser** le Bot à tout moment. Aucune données ne sera plus collectée à ton sujet.

### 📞 Droit de réclamation

En cas de problème, tu peux :
- Nous contacter directement (voir section 8)
- Introduire une réclamation auprès de la **CNIL** (France) : www.cnil.fr

---

## 6. 🔗 Partage des données

**Nous ne partageons AUCUNE donnée avec des tiers.**

Les seules exceptions :
- **APIs externes obligatoires** pour certaines fonctionnalités (avec ton consentement) :
  - Steam (pour `/cs2`)
  - Riot Games API (pour `/lol`, `/val`)
  - Ballchasing (pour `/rl`)
- **PandaScore** pour les données Esports (publiques)
- **Twitch/TikTok/Instagram APIs** pour les notifications

Ces APIs ne reçoivent **que** les données nécessaires (ex : ton pseudo Riot pour récupérer tes stats Valorant).

**Aucune donnée personnelle** n'est jamais vendue ou utilisée à des fins commerciales.

---

## 7. 🔄 Modifications de la politique

Cette politique peut être modifiée à tout moment. Les modifications :

- 📢 Seront **annoncées** via la commande `/changelog`
- 📅 Seront **datées** dans ce document (ci-dessus)
- 🌯 Seront **communiquées** sur Kebab Family

---

## 8. 📞 Contact

Pour toute question relative à cette Politique de Confidentialité, à tes données personnelles, ou à l'exercice de tes droits RGPD :

- 👤 **Responsable du traitement** : DealerDeKebab
- 💬 **Support** : [Kebab Family](https://discord.gg/s5ZJ3FQMYZ)
- 📧 **Contact direct** : DM Discord

**Délai de réponse** : Nous nous engageons à répondre à toute demande dans un délai de **30 jours maximum** conformément au RGPD.

---

## 9. 🌍 Autorité de contrôle

Conformément au RGPD, tu peux introduire une réclamation auprès de l'autorité de contrôle compétente :

**CNIL** (Commission Nationale de l'Informatique et des Libertés)
- 🌐 Site web : [www.cnil.fr](https://www.cnil.fr)
- 📞 Téléphone : 01 53 73 22 22
- 📮 Adresse : 3 Place de Fontenoy — TSA 80715 — 75334 PARIS CEDEX 07

---

*🌯 KebabBot • Politique de Confidentialité v1.0 • RGPD Compliant • Made with ❤️ in France*
