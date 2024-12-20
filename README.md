
# Agent de Diagnostic d’Imagerie Médicale

Un agent de diagnostic d’imagerie médicale développé avec **phidata** et alimenté par **Gemini 2.0 Flash Experimental**, offrant une analyse assistée par IA des images médicales de différents types de scans. L’agent agit comme un expert en diagnostic d’imagerie médicale pour analyser divers types d’images et vidéos médicales, en fournissant des informations diagnostiques détaillées et des explications.

## Fonctionnalités

- **Analyse Complète des Images**
  - *Identification du type d’image* (radiographie, IRM, scanner, échographie)
  - *Détection de la région anatomique*
  - *Principaux résultats et observations*
  - *Détection des anomalies potentielles*
  - *Évaluation de la qualité de l’image*
  - *Recherche et référence*

## Comment Lancer

1. **Configurer l’Environnement**
   ```bash
   # Cloner le dépôt
   git clone https://github.com/IbrahimaBailoDIALLO/AI_Agent/tree/main
   cd ai_agent_tutorials/ai_medical_imaging_agent

   # Installer les dépendances
   pip install -r requirements.txt
   ```

2. **Configurer les Clés API**
   - Obtenez une clé API Google depuis [Google AI Studio](https://aistudio.google.com)

3. **Exécuter l’Application**
   ```bash
   streamlit run ai_medical_imaging.py
   ```

## Composants d’Analyse

- **Type d’Image et Région**
  - Identifie la modalité d’imagerie
  - Spécifie la région anatomique

- **Principaux Résultats**
  - *Liste systématique des observations*
  - *Descriptions détaillées de l’apparence*
  - *Mise en évidence des anomalies*

- **Évaluation Diagnostique**
  - *Classement des diagnostics potentiels*
  - *Diagnostics différentiels*
  - *Évaluation de la gravité*

- **Explications Accessibles aux Patients**
  - *Terminologie simplifiée*
  - *Explications détaillées basées sur des principes fondamentaux*
  - *Points de référence visuels*

## Remarques

- **Utilise Gemini 2.0 Flash** pour l’analyse
- **Nécessite une connexion internet stable**
- **Des coûts d’utilisation de l’API peuvent s’appliquer**
- **Destiné uniquement à des fins éducatives et de développement**
- **Ne remplace pas un diagnostic médical professionnel**

## Avertissement

Cet outil est destiné à des fins éducatives et informatives uniquement. Toutes les analyses doivent être examinées par des professionnels de santé qualifiés. **Ne prenez pas de décisions médicales uniquement sur la base de cette analyse.**
