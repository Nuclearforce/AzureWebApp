# AzureWebApp
Run locally using: panel serve index.py datashaders.py interactivity.py streaming.py --index index.py

Change settings: Setting/Configuration/ 
    Web sockets = on
    Always on = on
    ARR affinity = on
    startup command: python -m panel serve app.py --address 0.0.0.0 --port 8000 --allow-websocket-origin=app-name.azurewebsites.net