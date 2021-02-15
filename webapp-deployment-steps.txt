# create ssh keys
ssh-keygen -t rsa

# create a new virtual environment with virtualenv tool, and name it venv
python3 -m venv venv

# activate the environment
source venv/bin/activate

# now install your dependencies
pip install -r requirements.txt

# export variable so the Azure stack knows which entry point to start your Flask app.    
export FLASK_RUN=app.py

# now deploy your code to an existing webapp in Azure cloud
az webapp up --sku F1 -n flaskhellobipin --resource-group rg-deployment-project