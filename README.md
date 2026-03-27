gaming-tracker/
├── .github/workflows/  # Automatische Tests (CI/CD)
│   └── python-app.yml
├── data/               # Speicherort für Spieldaten
│   └── games.json      # Hier landen deine Highscores/Listen
├── src/                # Dein Quellcode
│   ├── __init__.py
│   ├── api_handler.py  # (Optional) Für Steam/Twitch API-Anbindung
│   └── main.py         # Startpunkt deiner App
├── .gitignore          # Ignoriert venv/ und Cache
├── LICENSE             # Wähle die "MIT License" (sehr gängig)
├── requirements.txt    # Liste der Bibliotheken (z.B. rich, requests)
└── README.md           # Dein "Schaufenster"
