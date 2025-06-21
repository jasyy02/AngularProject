# AngularProject
Gestion de Portefeuille d'Actifs Numériques
PixelPrism est une application web conçue pour permettre aux utilisateurs de gérer facilement leur portefeuille d’actifs (actions, cryptomonnaies, etc.). Elle permet de suivre les investissements, visualiser la répartition des actifs, et voir la valeur totale du portefeuille en temps réel.
## 🌐 Technologies Utilisées

- **Frontend** : Angular
- **Backend** : Node.js, Express.js
- **Base de données** : MongoDB
- **Authentification** : JWT, BcryptJS
- **Autres outils** : Mongoose, Chart.js (optionnel), Tailwind/Angular Material (optionnel)

---

## 🚀 Fonctionnalités

- 🔐 Authentification sécurisée (inscription, connexion, déconnexion)
- 📁 Gestion de portefeuille (CRUD d’actifs : nom, quantité, valeur)
- 📊 Affichage dynamique des investissements
- 💸 Calcul de la valeur totale du portefeuille
- ⚙️ API RESTful simple et extensible

- 
---

##  Installation

###  Prérequis
- Node.js
- MongoDB 
- Angular CLI

### 🔧 Étapes

1. **Cloner le dépôt**
```bash
git clone https://github.com/votre-utilisateur/AngularProject.git
cd AngularProject
## ⚙️ Installation & Lancement

```yaml
#  Installation du backend
- cd backend
- npm install

# 🗂 Créer un fichier .env dans backend/
- PORT=5000
- MONGO_URI=mongodb://localhost:27017/fintrack
- JWT_SECRET=votre_secret

#  Lancer le backend
- node server.js

#  Installation du frontend (Angular)
- cd ../frontend
- npm install

#  Lancer Angular
- ng serve
