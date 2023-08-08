# ado-flask-aks-demo
CICD For AKS Env
# Origin app repo
- https://github.com/hyukjuns/simple-webapp

# CI
1. Install Docker CLI
2. Build and push Docker Image to ACR
(*Image Tag == Pipeline build number)

# CD
1. Trigger by Build pipeline success
2. Deploy to AKS (Deployment)
(*Image Tag == Pipeline build number (using Release pipeline Alias))

