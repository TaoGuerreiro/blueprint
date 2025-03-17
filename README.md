# Projet Django React Vite

Ce projet utilise Django pour le backend et React avec Vite pour le frontend.

## Prérequis

- Python 3.8+
- Node.js 18+
- npm ou yarn

## Installation

### Backend

1. Créer un environnement virtuel :
```bash
python -m venv venv
source venv/bin/activate  # Sur Unix/macOS
# ou
.\venv\Scripts\activate  # Sur Windows
```

2. Installer les dépendances :
```bash
pip install -r requirements.txt
```

3. Appliquer les migrations :
```bash
python manage.py migrate
```

4. Lancer le serveur Django :
```bash
python manage.py runserver
```

### Frontend

1. Se déplacer dans le dossier frontend :
```bash
cd frontend
```

2. Installer les dépendances :
```bash
npm install
```

3. Lancer le serveur de développement :
```bash
npm run dev
```

## Structure du projet

- `backend/` : Application Django
- `frontend/` : Application React avec Vite
- `api/` : Application Django pour l'API REST

## Accès

- Backend : http://localhost:8000
- Frontend : http://localhost:5173
