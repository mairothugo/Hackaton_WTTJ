# Hackaton_WTTJ
# 📬 Office Pulse – Automatisation RH Slack

Office Pulse est un système d'automatisation no-code pensé pour améliorer la coordination dans un contexte de travail hybride. Il s'appuie sur **Make.com**, **Slack**, **Google Sheets** et **Dust.ai** pour :

- Récupérer les présences hebdomadaires
- Générer des messages Slack personnalisés, engageants, sans pression
- Valoriser la présence au bureau grâce à un ton bienveillant et ludique

---

## 🛠️ Fonctionnalités

### ✅ 1. Scénario de récupération de présences (`blueprint-absences.json`)
- Lecture des présences depuis Google Sheets
- Identification des personnes n’ayant pas rempli leur formulaire
- Envoi d’un rappel automatisé via Slack DM

### 🎯 2. Scénario de message personnalisé (`blueprint-messages.json`)
- Analyse de données RH (lieu, équipe, goûts, projets…)
- Génération de message Slack sur-mesure via Dust (avec météo relationnelle)
- Envoi automatique dans un canal privé ou DM

---

## 🚀 Installation

### 1. Cloner le projet
```bash
git clone https://github.com/<votre-organisation>/office-pulse.git
cd office-pulse
