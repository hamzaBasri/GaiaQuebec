GaiaQuebec/
│
├── node_modules/                  # Dossiers de modules Node.js installés
│
├── src/                           # Dossier source principal
│   ├── config/                    # Configuration de l'application (base de données, etc.)
│   ├── controllers/               # Contrôleurs pour gérer la logique métier
│   ├── models/                    # Modèles de l'ORM (classes représentant les tables de la BD)
│   │   ├── Article.js             # Classe pour le modèle 'Article'
│   │   └── ...                    # Autres modèles
│   ├── routes/                    # Routes de l'API
│   ├── services/                  # Services pour la logique métier
│   ├── utils/                     # Utilitaires (fonctions d'aide, middleware, etc.)
│   └── app.js                     # Point d'entrée principal de l'application
│
├── public/                        # Fichiers statiques (images, fichiers CSS, etc.)
├── views/                         # Fichiers de template si vous utilisez un moteur de rendu
│
├── .env                           # Variables d'environnement
├── .gitignore                     # Fichiers à ignorer par Git
├── package.json                   # Dépendances et scripts NPM
└── README.md                      # Documentation du projet