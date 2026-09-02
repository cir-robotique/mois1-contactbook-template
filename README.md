# 📇 Mois 1 — ContactBook

**Centre Ivoirien de Robotique — Suivi 6 mois**

---

## 🎯 Ta mission

Tu viens d'être recruté comme développeur junior dans une agence digitale.
Ton manager t'appelle le premier jour :

> *"On a 200 contacts clients dans 4 fichiers Excel différents.
> Personne ne sait quelle version est la bonne.
> Tu as 5 jours pour nous faire quelque chose de propre."*

Tu vas construire **ContactBook** — une application web complète
permettant à chaque commercial de gérer ses contacts clients,
avec authentification, base de données et déploiement en production.

---

## 🛠 Stack technique

| Côté | Technologies |
|------|-------------|
| Frontend | React.js, React Router, Context API, Axios |
| Backend | Node.js, Express, JWT, bcrypt, Sequelize |
| Base de données | PostgreSQL (Railway) |
| Déploiement | Railway (API) + Vercel (Frontend) |

---

## 📋 Les 5 rubriques — 20 points au total

| # | Rubrique | Points |
|---|----------|--------|
| R1 | Authentification & Sécurité | 4 pts |
| R2 | Base de données PostgreSQL | 4 pts |
| R3 | API REST complète | 4 pts |
| R4 | Interface React | 4 pts |
| R5 | Déploiement & Documentation | 4 pts |
| | **TOTAL** | **20 pts** |

> ✅ **Seuil de déblocage Mois 2 : 17/20 (85%)**
>
> L'énoncé complet avec tous les critères détaillés est disponible sur Moodle.

---

## 📁 Structure attendue
contactbook/
api/ → Backend Node.js
frontend/ → Frontend React
README.md → Ton README final avec URL live

---

## 🚀 Pour commencer

```bash
# 1. Cloner ton repo
git clone https://github.com/cir-robotique/mois1-contactbook-[ton-pseudo].git

# 2. Configurer l'API
cd api
cp .env.example .env
# Remplir les valeurs dans .env
npm install

# 3. Configurer le frontend
cd ../frontend
npm install
npm run dev
```

---

## 📦 Livraison

Soumettre sur Moodle avant la deadline :

- 🔗 URL de ton repo GitHub
- 🔗 URL Railway (API)
- 🔗 URL Vercel (Frontend)

---

## ⚠️ Règles importantes

- Le fichier `.env` ne doit **jamais** être committé sur GitHub
- Au moins **10 commits** avec des messages explicites
- L'application doit fonctionner depuis les URLs de production
