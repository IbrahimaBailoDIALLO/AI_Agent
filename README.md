Agent de diagnostic d'imagerie médicale
Un agent de diagnostic d'imagerie médicale basé sur phidata optimisé par Gemini 2.0 Flash Experimental qui fournit une analyse assistée par IA d'images médicales de divers scanners. L'agent agit en tant qu'expert en diagnostic d'imagerie médicale pour analyser divers types d'images et de vidéos médicales, fournissant des informations et des explications diagnostiques détaillées.

Caractéristiques
Analyse d'image complète
Identification du type d'image (radiographie, IRM, tomodensitométrie, échographie)
Détection de région anatomique
Principales conclusions et observations
Détection d'anomalies potentielles
Évaluation de la qualité de l'image
Recherche et référence
Comment courir
Environnement de configuration

# Clone the repository
git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
cd ai_agent_tutorials/ai_medical_imaging_agent

# Install dependencies
pip install -r requirements.txt
Configurer les clés API

Obtenir la clé API Google depuis Google AI Studio
Exécuter l'application

streamlit run ai_medical_imaging.py
Composants d'analyse
Type d'image et région

Identifie la modalité d'imagerie
Spécifie la région anatomique
Principales conclusions

Liste systématique des observations
Descriptions détaillées des apparences
Mise en évidence des anomalies
Évaluation diagnostique

Classement des diagnostics potentiels
Diagnostics différentiels
Évaluation de la gravité
Explications adaptées aux patients

Terminologie simplifiée
Explications détaillées des premiers principes
Points de référence visuels
Remarques
Utilise Gemini 2.0 Flash pour l'analyse
Nécessite une connexion Internet stable
Des frais d'utilisation de l'API s'appliquent
À des fins éducatives et de développement uniquement
Ne remplace pas un diagnostic médical professionnel
Clause de non-responsabilité
Cet outil est fourni à des fins éducatives et informatives uniquement. Toutes les analyses doivent être examinées par des professionnels de la santé qualifiés. Ne prenez pas de décisions médicales basées uniquement sur cette analyse.
