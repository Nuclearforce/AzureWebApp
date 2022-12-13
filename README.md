# AzureWebApp
Run locally using (bash): 
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt

Make sure it works by running:
panel serve index.py datashaders.py interactivity.py streaming.py --index index.py

az webapp up --runtime PYTHON:3.10 --name <UniqueAppName> (remember to change the appname in the startup.txt file as well)
az webapp config set --startup-file startup.txt --web-sockets-enabled true -n <UniqueAppName> -g <resourcegroupname>

--allow-websocket-origin=paneldashboarddeploytestthree.azurewebsites.net or set BOKEH_ALLOW_WS_ORIGIN=paneldashboarddeploytestthree.azurewebsites.net