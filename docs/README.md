Projet de chat RAG
Ce projet est une application de chat utilisant la technique RAG (Retrieval-Augmented Generation). L'objectif est de démontrer l'amélioration des réponses d'un LLM (Large Language Model) en combinant une base de connaissances provenant du cloud avec des capacités de génération de texte.

Fonctionnalités
Comparaison avec et sans RAG : Posez la même question pour observer les différences dans les réponses du LLM.
Paramétrage du LLM : Modifiez la température pour voir l'impact sur la créativité des réponses.
Base de connaissances dynamique : Les documents sont récupérés à partir d'un service cloud.
Interface utilisateur intuitive : Une interface simple pour interagir avec le modèle.
Technologies utilisées
Backend : Python avec des frameworks comme Flask/FastAPI.
Front-end : HTML, CSS et JavaScript (vanille).
Cloud : Intégration avec [service cloud de votre choix, par ex. AWS S3, Google Cloud Storage].
Base de données : Pour stocker les informations liées aux documents (si nécessaire).
LLM : Utilisation d'Ollama ou d'une alternative supportant la technique RAG.
Installation

Clonez le dépôt Git :


git clone <URL_DU_DEPOT>
cd RAG_Chat_Project
Installez les dépendances du backend :

cd backend
pip install -r requirements.txt
Lancez le backend :




python app.py
Ouvrez l'interface utilisateur :

Naviguez dans le dossier frontend.
Ouvrez index.htmlun navigateur.
Structure du projet



RAG_Chat_Project/
├── backend/
│   ├── app.py            # Backend API
│   ├── requirements.txt  # Dépendances
├── frontend/
│   ├── index.html        # Interface utilisateur
│   ├── app.js            # Logique front-end
│   ├── styles.css        # Styles
├── data/
│   ├── example_data.json # Exemple de données
├── docs/
│   ├── README.md         # Documentation
Démonstration
Sans RAG : Posez une question pour obtenir une réponse uniquement basée sur le modèle.
Avec RAG : Activez l'intégration des documents cloud pour améliorer la réponse.
Paramètre température : Ajustez la température pour tester les variations de ton et de créativité.