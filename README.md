# AzureWebApp
Run locally using (bash): 
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt

Make sure it works by running:
panel serve index.py datashaders.py interactivity.py streaming.py --index index.py

Change settings: Setting/Configuration/ 
    Web sockets = on (It is on by default for linux)
    Always on = on
    ARR affinity = on

Used as an external git repo to update webapp